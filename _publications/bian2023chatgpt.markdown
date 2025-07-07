---
layout: publication
title: 'Chatgpt Is A Knowledgeable But Inexperienced Solver: An Investigation Of Commonsense
  Problem In Large Language Models'
authors: Ning Bian et al.
conference: Arxiv
year: 2023
citations: 36
bibkey: bian2023chatgpt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.16421'}]
tags: [GPT, RAG, Reinforcement Learning, Prompting, Model Architecture]
---
Large language models (LLMs) have made significant progress in NLP. However,
their ability to memorize, represent, and leverage commonsense knowledge has
been a well-known pain point. In this paper, we specifically focus on ChatGPT,
a widely used and easily accessible LLM, and ask the following questions: (1)
Can ChatGPT effectively answer commonsense questions? (2) Is ChatGPT aware of
the underlying commonsense knowledge for answering a specific question? (3) Is
ChatGPT knowledgeable in commonsense? (4) Can ChatGPT effectively leverage
commonsense for answering questions? We conduct a series of experiments on 11
datasets to evaluate ChatGPT's commonsense abilities, including answering
commonsense questions, identifying necessary knowledge, generating knowledge
descriptions, and using knowledge descriptions to answer questions again.
Experimental results show that: (1) ChatGPT can achieve good QA accuracies in
commonsense tasks, while still struggling with certain domains of datasets. (2)
ChatGPT is knowledgeable, and can accurately generate most of the commonsense
knowledge using knowledge prompts. (3) Despite its knowledge, ChatGPT is an
inexperienced commonsense problem solver, which cannot precisely identify the
needed commonsense for answering a specific question. These findings raise the
need to explore improved mechanisms for effectively incorporating commonsense
into LLMs like ChatGPT, such as better instruction following and commonsense
guidance.