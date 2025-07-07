---
layout: publication
title: Can Chatgpt Replace Traditional KBQA Models? An In-depth Analysis Of The Question
  Answering Performance Of The GPT LLM Family
authors: Yiming Tan et al.
conference: Arxiv
year: 2023
citations: 43
bibkey: tan2023can
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.07992'}, {name: Code,
    url: 'https://github.com/tan92hl/Complex-Question-Answering-Evaluation-of-GPT-family.git'}]
tags: [GPT, Reinforcement Learning, Tools, Has Code, Model Architecture]
---
ChatGPT is a powerful large language model (LLM) that covers knowledge
resources such as Wikipedia and supports natural language question answering
using its own knowledge. Therefore, there is growing interest in exploring
whether ChatGPT can replace traditional knowledge-based question answering
(KBQA) models. Although there have been some works analyzing the question
answering performance of ChatGPT, there is still a lack of large-scale,
comprehensive testing of various types of complex questions to analyze the
limitations of the model. In this paper, we present a framework that follows
the black-box testing specifications of CheckList proposed by Ribeiro et. al.
We evaluate ChatGPT and its family of LLMs on eight real-world KB-based complex
question answering datasets, which include six English datasets and two
multilingual datasets. The total number of test cases is approximately 190,000.
In addition to the GPT family of LLMs, we also evaluate the well-known FLAN-T5
to identify commonalities between the GPT family and other LLMs. The dataset
and code are available at
https://github.com/tan92hl/Complex-Question-Answering-Evaluation-of-GPT-family.git