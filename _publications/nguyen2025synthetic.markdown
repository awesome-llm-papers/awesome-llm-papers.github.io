---
layout: publication
title: Synthetic Text Generation For Training Large Language Models Via Gradient Matching
authors: Nguyen et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2025
bibkey: nguyen2025synthetic
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.17607'}]
tags: [Training Techniques, Efficiency And Optimization, Fine Tuning, ACL, EMNLP,
  RAG, Language Modeling, Alt]
---
Synthetic data has the potential to improve the performance, training efficiency, and privacy of real training examples. Nevertheless, existing approaches for synthetic text generation are mostly heuristics and cannot generate human-readable text without compromising the privacy of real data, or provide performance guarantees for training Large Language Models (LLMs). In this work, we propose the first theoretically rigorous approach for generating synthetic human-readable text that provides convergence, performance, and privacy guarantees for fine-tuning LLMs on a target task. To do so, we leverage Alternating Direction Method of Multipliers (ADMM) that iteratively optimizes the embeddings of synthetic examples to match the noisy gradient of the target training or validation data, and maps them to a sequence of text tokens with low perplexity. In doing so, the generated synthetic text guarantees convergence of the model to a close neighborhood of the solution obtained by fine-tuning on real data and preserves their privacy. Experiments on various classification tasks confirm the effectiveness of our proposed approach. Our code is available at https://github.com/BigML-CS-UCLA/GRADMM.