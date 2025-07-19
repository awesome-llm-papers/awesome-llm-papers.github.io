---
layout: publication
title: 'Finmteb: Finance Massive Text Embedding Benchmark'
authors: Tang Yixuan, Yang Yi
conference: Proceedings of the 17th Conference of the European Chapter of the Association
  for Computational Linguistics
year: 2025
bibkey: tang2025finmteb
citations: 134
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.10990'}]
tags: [Tools, Training Techniques, Datasets, Evaluation, ACL, Applications, EACL,
  Reinforcement Learning]
---
Embedding models play a crucial role in representing and retrieving
information across various NLP applications. Recent advances in large language
models (LLMs) have further enhanced the performance of embedding models. While
these models are often benchmarked on general-purpose datasets, real-world
applications demand domain-specific evaluation. In this work, we introduce the
Finance Massive Text Embedding Benchmark (FinMTEB), a specialized counterpart
to MTEB designed for the financial domain. FinMTEB comprises 64 financial
domain-specific embedding datasets across 7 tasks that cover diverse textual
types in both Chinese and English, such as financial news articles, corporate
annual reports, ESG reports, regulatory filings, and earnings call transcripts.
We also develop a finance-adapted model, Fin-E5, using a persona-based data
synthetic method to cover diverse financial embedding tasks for training.
Through extensive evaluation of 15 embedding models, including Fin-E5, we show
three key findings: (1) performance on general-purpose benchmarks shows limited
correlation with financial domain tasks; (2) domain-adapted models consistently
outperform their general-purpose counterparts; and (3) surprisingly, a simple
Bag-of-Words (BoW) approach outperforms sophisticated dense embeddings in
financial Semantic Textual Similarity (STS) tasks, underscoring current
limitations in dense embedding techniques. Our work establishes a robust
evaluation framework for financial NLP applications and provides crucial
insights for developing domain-specific embedding models.