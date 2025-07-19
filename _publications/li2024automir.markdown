---
layout: publication
title: 'Automir: Effective Zero-shot Medical Information Retrieval Without Relevance
  Labels'
authors: Li et al.
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2024
bibkey: li2024automir
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.20050'}]
tags: [Tools, Evaluation, ACL, RAG, Datasets, Reinforcement Learning, Alt]
---
Medical information retrieval (MIR) is essential for retrieving relevant medical knowledge from diverse sources, including electronic health records, scientific literature, and medical databases. However, achieving effective zero-shot dense retrieval in the medical domain poses substantial challenges due to the lack of relevance-labeled data. In this paper, we introduce a novel approach called \textbf\{S\}elf-\textbf\{L\}earning \textbf\{Hy\}pothetical \textbf\{D\}ocument \textbf\{E\}mbeddings (\textbf\{SL-HyDE\}) to tackle this issue. SL-HyDE leverages large language models (LLMs) as generators to generate hypothetical documents based on a given query. These generated documents encapsulate key medical context, guiding a dense retriever in identifying the most relevant documents. The self-learning framework progressively refines both pseudo-document generation and retrieval, utilizing unlabeled medical corpora without requiring any relevance-labeled data. Additionally, we present the Chinese Medical Information Retrieval Benchmark (CMIRB), a comprehensive evaluation framework grounded in real-world medical scenarios, encompassing five tasks and ten datasets. By benchmarking ten models on CMIRB, we establish a rigorous standard for evaluating medical information retrieval systems. Experimental results demonstrate that SL-HyDE significantly surpasses HyDE in retrieval accuracy while showcasing strong generalization and scalability across various LLM and retriever configurations. Our code and data are publicly available at: https://github.com/ll0ruc/AutoMIR