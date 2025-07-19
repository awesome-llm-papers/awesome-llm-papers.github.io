---
layout: publication
title: 'LLM Echo Chamber: Personalized And Automated Disinformation'
authors: Ma Tony
conference: Journal of Applied Research in Memory and Cognition
year: 2024
bibkey: ma2024llm
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.16241'}]
tags: [Model Architecture, Reinforcement Learning, Datasets, GPT]
---
Recent advancements have showcased the capabilities of Large Language Models
like GPT4 and Llama2 in tasks such as summarization, translation, and content
review. However, their widespread use raises concerns, particularly around the
potential for LLMs to spread persuasive, humanlike misinformation at scale,
which could significantly influence public opinion. This study examines these
risks, focusing on LLMs ability to propagate misinformation as factual. To
investigate this, we built the LLM Echo Chamber, a controlled digital
environment simulating social media chatrooms, where misinformation often
spreads. Echo chambers, where individuals only interact with like minded
people, further entrench beliefs. By studying malicious bots spreading
misinformation in this environment, we can better understand this phenomenon.
We reviewed current LLMs, explored misinformation risks, and applied sota
finetuning techniques. Using Microsoft phi2 model, finetuned with our custom
dataset, we generated harmful content to create the Echo Chamber. This setup,
evaluated by GPT4 for persuasiveness and harmfulness, sheds light on the
ethical concerns surrounding LLMs and emphasizes the need for stronger
safeguards against misinformation.