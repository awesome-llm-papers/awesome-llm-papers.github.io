---
layout: publication
title: 'Beyond Independent Passages: Adaptive Passage Combination Retrieval For Retrieval
  Augmented Open-domain Question Answering'
authors: Ko Ting-wen, Jiang Jyun-yu, Cheng Pu-jen
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2025
bibkey: ko2025beyond
citations: 980
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2507.04069'}]
tags: [RAG, EMNLP, Training Techniques, Tools, Evaluation, Reinforcement Learning,
  Datasets]
---
Retrieval-augmented generation (RAG) enhances large language models (LLMs) by incorporating external documents at inference time, enabling up-to-date knowledge access without costly retraining. However, conventional RAG methods retrieve passages independently, often leading to redundant, noisy, or insufficiently diverse context-particularly problematic - particularly problematic in noisy corpora and for multi-hop questions. To address this, we propose Adaptive Passage Combination Retrieval (AdaPCR), a novel framework for open-domain question answering with black-box LMs. AdaPCR explicitly models dependencies between passages by considering passage combinations as units for retrieval and reranking. It consists of a context-aware query reformulation using concatenated passages, and a reranking step trained with a predictive objective aligned with downstream answer likelihood. Crucially, AdaPCR adaptively selects the number of retrieved passages without additional stopping modules. Experiments across several QA benchmarks show that AdaPCR outperforms baselines, particularly in multi-hop reasoning, demonstrating the effectiveness of modeling inter-passage dependencies for improved retrieval.