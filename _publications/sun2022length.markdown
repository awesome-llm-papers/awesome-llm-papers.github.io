---
layout: publication
title: A Length-extrapolatable Transformer
authors: Yutao Sun et al.
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
citations: 19
bibkey: sun2022length
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.10554'}, {name: Code,
    url: 'https://aka.ms/LeX-Transformer'}]
tags: [Language Modeling, Has Code, Model Architecture, Attention Mechanism, Transformer,
  Training Techniques]
---
Position modeling plays a critical role in Transformers. In this paper, we
focus on length extrapolation, i.e., training on short texts while evaluating
longer sequences. We define attention resolution as an indicator of
extrapolation. Then we propose two designs to improve the above metric of
Transformers. Specifically, we introduce a relative position embedding to
explicitly maximize attention resolution. Moreover, we use blockwise causal
attention during inference for better resolution. We evaluate different
Transformer variants with language modeling. Experimental results show that our
model achieves strong performance in both interpolation and extrapolation
settings. The code will be available at https://aka.ms/LeX-Transformer.