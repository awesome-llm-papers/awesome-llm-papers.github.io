---
layout: publication
title: 'Lllms: A Data-driven Survey Of Evolving Research On Limitations Of Large Language
  Models'
authors: Kostikova et al.
conference: Natural Language Processing Journal
year: 2025
bibkey: kostikova2025lllms
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.19240'}]
tags: [Datasets, Tools, Ethics And Bias, BERT, Model Architecture, Survey Paper, Reinforcement
    Learning, Security, Multimodal Models, Responsible AI]
---
Large language model (LLM) research has grown rapidly, along with increasing concern about their limitations such as failures in reasoning, hallucinations, and limited multilingual capability. While prior reviews have addressed these issues, they often focus on individual limitations or consider them within the broader context of evaluating overall model performance. This survey addresses the gap by presenting a data-driven, semi-automated review of research on limitations of LLMs (LLLMs) from 2022 to 2025, using a bottom-up approach. From a corpus of 250,000 ACL and arXiv papers, we extract 14,648 relevant limitation papers using keyword filtering and LLM-based classification, validated against expert labels. Using topic clustering (via two approaches, HDBSCAN+BERTopic and LlooM), we identify between 7 and 15 prominent types of limitations discussed in recent LLM research across the ACL and arXiv datasets. We find that LLM-related research increases nearly sixfold in ACL and nearly fifteenfold in arXiv between 2022 and 2025, while LLLMs research grows even faster, by a factor of over 12 in ACL and nearly 28 in arXiv. Reasoning remains the most studied limitation, followed by generalization, hallucination, bias, and security. The distribution of topics in the ACL dataset stays relatively stable over time, while arXiv shifts toward safety and controllability (with topics like security risks, alignment, hallucinations, knowledge editing), and multimodality between 2022 and 2025. We offer a quantitative view of trends in LLM limitations research and release a dataset of annotated abstracts and a validated methodology, available at: https://github.com/a-kostikova/LLLMs-Survey.