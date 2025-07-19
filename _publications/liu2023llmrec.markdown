---
layout: publication
title: 'Llmrec: Benchmarking Large Language Models On Recommendation Task'
authors: Liu et al.
conference: Proceedings of the 17th ACM International Conference on Web Search and
  Data Mining
year: 2023
bibkey: liu2023llmrec
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.12241'}]
tags: [Interpretability And Explainability, GPT, Evaluation, Model Architecture, Datasets]
---
Recently, the fast development of Large Language Models (LLMs) such as
ChatGPT has significantly advanced NLP tasks by enhancing the capabilities of
conversational models. However, the application of LLMs in the recommendation
domain has not been thoroughly investigated. To bridge this gap, we propose
LLMRec, a LLM-based recommender system designed for benchmarking LLMs on
various recommendation tasks. Specifically, we benchmark several popular
off-the-shelf LLMs, such as ChatGPT, LLaMA, ChatGLM, on five recommendation
tasks, including rating prediction, sequential recommendation, direct
recommendation, explanation generation, and review summarization. Furthermore,
we investigate the effectiveness of supervised finetuning to improve LLMs'
instruction compliance ability. The benchmark results indicate that LLMs
displayed only moderate proficiency in accuracy-based tasks such as sequential
and direct recommendation. However, they demonstrated comparable performance to
state-of-the-art methods in explainability-based tasks. We also conduct
qualitative evaluations to further evaluate the quality of contents generated
by different models, and the results show that LLMs can truly understand the
provided information and generate clearer and more reasonable results. We
aspire that this benchmark will serve as an inspiration for researchers to
delve deeper into the potential of LLMs in enhancing recommendation
performance. Our codes, processed data and benchmark results are available at
https://github.com/williamliujl/LLMRec.