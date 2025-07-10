---
layout: publication
title: 'Wikichat: Stopping The Hallucination Of Large Language Model Chatbots By Few-shot
  Grounding On Wikipedia'
authors: Sina J. Semnani, Violet Z. Yao, Heidi C. Zhang, Monica S. Lam
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2023
citations: 15
bibkey: semnani2023stopping
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.14292'}]
tags: [GPT, Few-Shot, Model Architecture, Evaluation]
---
This paper presents the first few-shot LLM-based chatbot that almost never
hallucinates and has high conversationality and low latency. WikiChat is
grounded on the English Wikipedia, the largest curated free-text corpus.
  WikiChat generates a response from an LLM, retains only the grounded facts,
and combines them with additional information it retrieves from the corpus to
form factual and engaging responses. We distill WikiChat based on GPT-4 into a
7B-parameter LLaMA model with minimal loss of quality, to significantly improve
its latency, cost and privacy, and facilitate research and deployment.
  Using a novel hybrid human-and-LLM evaluation methodology, we show that our
best system achieves 97.3% factual accuracy in simulated conversations. It
significantly outperforms all retrieval-based and LLM-based baselines, and by
3.9%, 38.6% and 51.0% on head, tail and recent knowledge compared to GPT-4.
Compared to previous state-of-the-art retrieval-based chatbots, WikiChat is
also significantly more informative and engaging, just like an LLM.
  WikiChat achieves 97.9% factual accuracy in conversations with human users
about recent topics, 55.0% better than GPT-4, while receiving significantly
higher user ratings and more favorable comments.