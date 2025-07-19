---
layout: publication
title: 'Loki: Low-rank Keys For Efficient Sparse Attention'
authors: Singhania et al.
conference: IEEE Transactions on Pattern Analysis and Machine Intelligence
year: 2024
bibkey: singhania2024loki
citations: 112
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.02542'}]
tags: [Model Architecture, Evaluation, LLM for Code, Transformer, Datasets, Attention
    Mechanism]
---
Inference on large language models (LLMs) can be expensive in terms of the
compute and memory costs involved, especially when long sequence lengths are
used. In particular, the self-attention mechanism used in LLM inference
contributes significantly to these costs, which has sparked an interest in
approximating the self-attention computation to reduce such costs. In this
work, we propose to approximate self-attention by focusing on the
dimensionality of key vectors computed in the attention block. Our analysis
reveals that key vectors lie in a significantly lower-dimensional space,
consistently across several datasets and models. Exploiting this observation,
we propose Loki, a novel sparse attention method that ranks and selects tokens
in the KV-cache based on attention scores computed in low-dimensional space.
Our evaluations show that Loki is able to speed up the attention computation
due to reduced data movement (load/store) and compute costs while maintaining
the efficacy of the models better than other popular approximation methods.