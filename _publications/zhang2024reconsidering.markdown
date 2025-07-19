---
layout: publication
title: Reconsidering Degeneration Of Token Embeddings With Definitions For Encoder-based
  Pre-trained Language Models
authors: Zhang Ying, Li Dongyuan, Okumura Manabu
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2024
bibkey: zhang2024reconsidering
citations: 260
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2408.01308'}]
tags: [RAG, EMNLP, Training Techniques, BERT, Model Architecture, Security, Fine Tuning,
  Datasets]
---
Learning token embeddings based on token co-occurrence statistics has proven
effective for both pre-training and fine-tuning in natural language processing.
However, recent studies have pointed out that the distribution of learned
embeddings degenerates into anisotropy (i.e., non-uniform distribution), and
even pre-trained language models (PLMs) suffer from a loss of semantics-related
information in embeddings for low-frequency tokens. This study first analyzes
the fine-tuning dynamics of encoder-based PLMs and demonstrates their
robustness against degeneration. On the basis of this analysis, we propose
DefinitionEMB, a method that utilizes definitions to re-construct isotropically
distributed and semantics-related token embeddings for encoder-based PLMs while
maintaining original robustness during fine-tuning. Our experiments demonstrate
the effectiveness of leveraging definitions from Wiktionary to re-construct
such embeddings for two encoder-based PLMs: RoBERTa-base and BART-large.
Furthermore, the re-constructed embeddings for low-frequency tokens improve the
performance of these models across various GLUE and four text summarization
datasets.