---
layout: publication
title: Optimization Methods For Personalizing Large Language Models Through Retrieval
  Augmentation
authors: Alireza Salemi, Surya Kallumadi, Hamed Zamani
conference: 'SIGIR 2024: The 47th International ACM SIGIR Conference on Research and
  Development in Information Retrieval'
year: 2024
citations: 18
bibkey: salemi2024optimization
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.05970'}]
tags: [Distillation, RAG, Applications, Reinforcement Learning, Efficiency and Optimization,
  Evaluation]
---
This paper studies retrieval-augmented approaches for personalizing large
language models (LLMs), which potentially have a substantial impact on various
applications and domains. We propose the first attempt to optimize the
retrieval models that deliver a limited number of personal documents to large
language models for the purpose of personalized generation. We develop two
optimization algorithms that solicit feedback from the downstream personalized
generation tasks for retrieval optimization -- one based on reinforcement
learning whose reward function is defined using any arbitrary metric for
personalized generation and another based on knowledge distillation from the
downstream LLM to the retrieval model. This paper also introduces a pre- and
post-generation retriever selection model that decides what retriever to choose
for each LLM input. Extensive experiments on diverse tasks from the language
model personalization (LaMP) benchmark reveal statistically significant
improvements in six out of seven datasets.