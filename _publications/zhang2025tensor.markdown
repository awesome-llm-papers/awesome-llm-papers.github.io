---
layout: publication
title: Tensor Product Attention Is All You Need
authors: Yifan Zhang, Yifeng Liu, Huizhuo Yuan, Zhen Qin, Yang Yuan, Quanquan Gu,
  Andrew Chi-chih Yao
conference: No Venue
year: 2025
bibkey: zhang2025tensor
additional_links: [{name: Code, url: 'https://github.com/tensorgi/T6'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/6785ce63cb1fc2728334a639'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2501.06425'}]
tags: ["Model Architecture"]
short_authors: Zhang et al.
---
Scaling language models to handle longer input sequences typically necessitates large key-value (KV) caches, resulting in substantial memory overhead during inference. In this paper, we propose Tensor Product Attention (TPA), a novel attention mechanism that uses tensor decompositions to represent queries, keys, and values compactly, significantly shrinking KV cache size at inference time. By factorizing these representations into contextual low-rank components (contextual factorization) and seamlessly integrating with RoPE, TPA achieves improved model quality alongside memory efficiency. Based on TPA, we introduce the Tensor ProducT ATTenTion Transformer (T6), a new model architecture for sequence modeling. Through extensive empirical evaluation of language modeling tasks, we demonstrate that T6 exceeds the performance of standard Transformer baselines including MHA, MQA, GQA, and MLA across various metrics, including perplexity and a range of renowned evaluation benchmarks. Notably, TPAs memory efficiency enables the processing of significantly longer sequences under fixed resource constraints, addressing a critical scalability challenge in modern language models. The code is available at https://github.com/tensorgi/T6.

https://huggingface.co/discussions/paper/6785ce63cb1fc2728334a639