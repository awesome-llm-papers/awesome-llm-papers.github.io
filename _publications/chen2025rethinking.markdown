---
layout: publication
title: 'Rethinking All Evidence: Enhancing Trustworthy Retrieval-augmented Generation
  Via Conflict-driven Summarization'
authors: Chen et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2021'
year: 2025
bibkey: chen2025rethinking
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2507.01281'}]
tags: [Tools, Evaluation, ACL, EMNLP, RAG, Datasets]
---
Retrieval-Augmented Generation (RAG) enhances large language models (LLMs) by integrating their parametric knowledge with external retrieved content. However, knowledge conflicts caused by internal inconsistencies or noisy retrieved content can severely undermine the generation reliability of RAG systems.In this work, we argue that LLMs should rethink all evidence, including both retrieved content and internal knowledge, before generating responses.We propose CARE-RAG (Conflict-Aware and Reliable Evidence for RAG), a novel framework that improves trustworthiness through Conflict-Driven Summarization of all available evidence.CARE-RAG first derives parameter-aware evidence by comparing parameter records to identify diverse internal perspectives. It then refines retrieved evidences to produce context-aware evidence, removing irrelevant or misleading content. To detect and summarize conflicts, we distill a 3B LLaMA3.2 model to perform conflict-driven summarization, enabling reliable synthesis across multiple sources.To further ensure evaluation integrity, we introduce a QA Repair step to correct outdated or ambiguous benchmark answers.Experiments on revised QA datasets with retrieval data show that CARE-RAG consistently outperforms strong RAG baselines, especially in scenarios with noisy or conflicting evidence.