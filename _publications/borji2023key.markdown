---
layout: publication
title: Key-value Transformer
authors: Borji Ali
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2023
bibkey: borji2023key
citations: 171
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.19129'}]
tags: [RAG, EMNLP, Attention Mechanism, Evaluation, Transformer, Model Architecture]
---
Transformers have emerged as the prevailing standard solution for various AI
tasks, including computer vision and natural language processing. The widely
adopted Query, Key, and Value formulation (QKV) has played a significant role
in this. Nevertheless, no research has examined the essentiality of these three
components for transformer performance. Therefore, we conducted an evaluation
of the key-value formulation (KV), which generates symmetric attention maps,
along with an asymmetric version that incorporates a 2D positional encoding
into the attention matrix. Remarkably, this transformer requires fewer
parameters and computation than the original one. Through experiments
encompassing three task types -- synthetics (such as reversing or sorting a
list), vision (mnist or cifar classification), and NLP (character generation
and translation) -- we discovered that the KV transformer occasionally
outperforms the QKV transformer. However, it also exhibits instances of
underperformance compared to QKV, making it challenging to draw a definitive
conclusion. Nonetheless, we consider the reported results to be encouraging and
anticipate that they may pave the way for more efficient transformers in the
future.