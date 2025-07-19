---
layout: publication
title: 'Tool Calling: Enhancing Medication Consultation Via Retrieval-augmented Large
  Language Models'
authors: Huang et al.
conference: 4th ACM International Conference on AI in Finance
year: 2024
bibkey: huang2024tool
citations: 89
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.17897'}]
tags: [RAG, Distillation, Tools, Evaluation, Efficiency And Optimization, Reinforcement
    Learning, Datasets]
---
Large-scale language models (LLMs) have achieved remarkable success across
various language tasks but suffer from hallucinations and temporal
misalignment. To mitigate these shortcomings, Retrieval-augmented generation
(RAG) has been utilized to provide external knowledge to facilitate the answer
generation. However, applying such models to the medical domain faces several
challenges due to the lack of domain-specific knowledge and the intricacy of
real-world scenarios. In this study, we explore LLMs with RAG framework for
knowledge-intensive tasks in the medical field. To evaluate the capabilities of
LLMs, we introduce MedicineQA, a multi-round dialogue benchmark that simulates
the real-world medication consultation scenario and requires LLMs to answer
with retrieved evidence from the medicine database. MedicineQA contains 300
multi-round question-answering pairs, each embedded within a detailed dialogue
history, highlighting the challenge posed by this knowledge-intensive task to
current LLMs. We further propose a new \textit\{Distill-Retrieve-Read\} framework
instead of the previous \textit\{Retrieve-then-Read\}. Specifically, the
distillation and retrieval process utilizes a tool calling mechanism to
formulate search queries that emulate the keyword-based inquiries used by
search engines. With experimental results, we show that our framework brings
notable performance improvements and surpasses the previous counterparts in the
evidence retrieval process in terms of evidence retrieval accuracy. This
advancement sheds light on applying RAG to the medical domain.