---
layout: publication
title: 'Benchmarking The Myopic Trap: Positional Bias In Information Retrieval'
authors: Zeng et al.
conference: Proceedings of the 32nd international ACM SIGIR conference on Research
  and development in information retrieval
year: 2025
bibkey: zeng2025benchmarking
citations: 123
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.13950'}]
tags: [RAG, Training Techniques, Tools, Evaluation, Ethics And Bias, BERT, Model Architecture,
  Reinforcement Learning, SIGIR, Security, Datasets]
---
This study investigates a specific form of positional bias, termed the Myopic Trap, where retrieval models disproportionately attend to the early parts of documents while overlooking relevant information that appears later. To systematically quantify this phenomenon, we propose a semantics-preserving evaluation framework that repurposes the existing NLP datasets into position-aware retrieval benchmarks. By evaluating the SOTA models of full retrieval pipeline, including BM25, embedding models, ColBERT-style late-interaction models, and reranker models, we offer a broader empirical perspective on positional bias than prior work. Experimental results show that embedding models and ColBERT-style models exhibit significant performance degradation when query-related content is shifted toward later positions, indicating a pronounced head bias. Notably, under the same training configuration, ColBERT-style approach show greater potential for mitigating positional bias compared to the traditional single-vector approach. In contrast, BM25 and reranker models remain largely unaffected by such perturbations, underscoring their robustness to positional bias. Code and data are publicly available at: www.github.com/NovaSearch-Team/RAG-Retrieval.