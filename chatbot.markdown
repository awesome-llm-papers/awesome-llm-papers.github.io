---
layout: page
title: Chat with the Awesome-LLM-Papers Bot
description: Awesome-LLM-Papers Chatbot
---
The Awesome-LLM-Papers Chatbot can help you find relevant papers, with over 5,000 papers (and growing) currently ingested into the Bot's knowledge base.

<div class="container">
    <h3>Example Queries</h3>
    <ul id="popular-queries-list"></ul>
</div>

Feel free to ask any of your own questions!

<div class="chat-layout">
  <div class="chat-container">
    <div class="chatbox">
      <div id="messages" class="messages"></div>

      <div id="loading" style="display: none; text-align: center; padding: 10px;">
        <span class="spinner"></span> Retrieving response...
      </div>

      <div class="input-area">
        <input id="query" type="text" placeholder="Ask a question..." class="chat-input">
        <button onclick="sendQuery()" class="send-button">Send</button>
      </div>
    </div>
  </div>
</div>

<style>
html, body {
  height: 100%;
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  display: flex;
  flex-direction: column;
}

.chat-layout {
  flex: 1;
  display: flex;
  flex-direction: column;
  height: 100%;
}

.chat-container {
  flex: 1;
  display: flex;
  justify-content: center;
  align-items: stretch;
  padding: 10px;
}

.chatbox {
  flex: 1;
  display: flex;
  flex-direction: column;
  width: 90%;
  max-width: 900px;
  min-width: 400px;
  border-radius: 10px;
  overflow: hidden;
  background-color: #ffffff;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.messages {
  flex: 1;
  padding: 15px;
  overflow-y: auto;
  border-bottom: 1px solid #e0e0e0;
}

.message {
  padding: 10px;
  margin-bottom: 10px;
  border-radius: 10px;
  max-width: 80%;
  word-wrap: break-word;
}

.user {
  align-self: flex-end;
  background-color: #d1e7ff; /* Light blue */
  text-align: right;
}

.bot {
  align-self: flex-start;
  background-color: #e8f5e9; /* Light green */
  text-align: left;
}

.input-area {
  display: flex;
  padding: 10px;
  border-top: 1px solid #e0e0e0;
  background-color: #fafafa;
}

.chat-input {
  flex-grow: 1;
  padding: 15px;
  font-size: 16px;
  border: 1px solid #ccc;
  border-radius: 5px;
  outline: none;
  width: 100%;
}

.send-button {
  margin-left: 10px;
  padding: 15px 25px;
  background-color: #2196f3;
  color: #fff;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.send-button:hover {
  background-color: #1e88e5;
}

/* Spinner */
.spinner {
  display: inline-block;
  width: 24px;
  height: 24px;
  border: 3px solid rgba(0,0,0,0.2);
  border-top: 3px solid #2196f3;
  border-radius: 50%;
  animation: spin 1s linear infinite;
  vertical-align: middle;
  margin-right: 8px;
}

@keyframes spin {
  to { transform: rotate(360deg); }
}
</style>

<script>
// Fetch popular queries from your Flask endpoint
fetch("https://awesome-llm-papers.tinyapps.run/popular-queries")
    .then(response => response.json())
    .then(data => {
        const queriesList = document.getElementById("popular-queries-list");

        if (data.length === 0) {
            const defaultMessage = document.createElement("li");
            defaultMessage.textContent = "No queries yet";
            queriesList.appendChild(defaultMessage);
        } else {
            const shuffledData = data.sort(() => 0.5 - Math.random()).slice(0, 5);
            shuffledData.forEach(item => {
                const listItem = document.createElement("li");
                listItem.innerHTML = `<strong>${capitalizeFirstLetter(item.query)}</strong>`;
                queriesList.appendChild(listItem);
            });
        }
    })
    .catch(error => {
        console.error("Error loading popular queries:", error);
    });

function capitalizeFirstLetter(query) {
    return query.charAt(0).toUpperCase() + query.slice(1);
}
</script>

<script>
window.onload = function() {
  displayWelcomeMessage();
};

async function sendQuery() {
  const query = document.getElementById("query").value;
  const messagesDiv = document.getElementById("messages");
  const loadingDiv = document.getElementById("loading");

  appendMessage("user", "You: " + query);
  document.getElementById("query").value = "";

  loadingDiv.style.display = "block"; // Show spinner

  try {
    const response = await fetch("https://awesome-llm-papers.tinyapps.run/chat", {
      method: "POST",
      headers: { "Content-Type": "application/json" },
      body: JSON.stringify({ user_input: query })
    });

    if (response.status === 429) {
      displayBotMessage("Rate limit reached, please try again tomorrow.");
      return;
    }

    if (!response.ok) {
      const errorData = await response.json();
      throw new Error(errorData.error || "Unknown error occurred");
    }

    const result = await response.json();
    if (result.answer) {
      parseAndDisplayAnswer(result.answer);
    } else {
      displayBotMessage("No answer field found in the response.");
    }
  } catch (error) {
    displayBotMessage(`Error - ${error.message}`);
  } finally {
    loadingDiv.style.display = "none"; // Hide spinner after fetch
    messagesDiv.scrollTop = messagesDiv.scrollHeight;
  }
}

function displayWelcomeMessage() {
  displayBotMessage("Hello! I'm the Awesome LLM Papers Bot. How can I assist you today?");
}

function parseAndDisplayAnswer(answer) {
  try {
    let papers = answer;

    if (typeof answer === "string") {
      const jsonStart = answer.indexOf("[");
      const jsonEnd = answer.lastIndexOf("]") + 1;
      if (jsonStart === -1 || jsonEnd === -1) {
        throw new Error("No valid JSON block found.");
      }
      const jsonString = answer.substring(jsonStart, jsonEnd);
      papers = JSON.parse(jsonString);
    }

    if (!Array.isArray(papers)) throw new Error("Expected array of papers.");

    const botMessage = document.createElement("div");
    botMessage.classList.add("message", "bot");
    botMessage.innerHTML = `<p>Awesome LLM Papers Bot:</p><ul>${formatBotResponse(papers)}</ul>`;
    document.getElementById("messages").appendChild(botMessage);
  } catch (jsonError) {
    displayBotMessage("Error parsing the response data.");
  }
}

function displayBotMessage(text) {
  const errorMessage = document.createElement("div");
  errorMessage.classList.add("message", "bot");
  errorMessage.textContent = `Awesome LLM Papers Bot: ${text}`;
  document.getElementById("messages").appendChild(errorMessage);
}

function appendMessage(className, text) {
  const message = document.createElement("div");
  message.classList.add("message", className);
  message.textContent = text;
  document.getElementById("messages").appendChild(message);
}

function formatBotResponse(papers) {
  if (!Array.isArray(papers)) {
    return "<li>No papers found.</li>";
  }

  return papers.map(paper => `
    <li><strong><a href="${paper.url}" target="_blank">${capitalizeTitle(paper.name)}</a></strong>: ${capitalizeSentence(paper.description)}</li>
  `).join('');
}

function capitalizeTitle(title) {
  const minorWords = ["the", "in", "and", "of", "to", "for"];
  return title.split(" ").map((word, index) => {
    if (minorWords.includes(word.toLowerCase()) && index !== 0) {
      return word.toLowerCase();
    }
    return word.charAt(0).toUpperCase() + word.slice(1).toLowerCase();
  }).join(" ");
}

function capitalizeSentence(sentence) {
  return sentence.charAt(0).toUpperCase() + sentence.slice(1);
}
</script>
