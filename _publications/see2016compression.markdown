---
layout: publication
title: Compression Of Neural Machine Translation Models Via Pruning
authors: Abigail See, Minh-thang Luong, Christopher D. Manning
conference: Proceedings of The 20th SIGNLL Conference on Computational Natural Language
  Learning
year: 2016
bibkey: see2016compression
citations: 165
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.09274'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Abigail See, Minh-thang Luong, Christopher D. Manning
---
Neural Machine Translation (NMT), like many other deep learning domains,
typically suffers from over-parameterization, resulting in large storage sizes.
This paper examines three simple magnitude-based pruning schemes to compress
NMT models, namely class-blind, class-uniform, and class-distribution, which
differ in terms of how pruning thresholds are computed for the different
classes of weights in the NMT architecture. We demonstrate the efficacy of
weight pruning as a compression technique for a state-of-the-art NMT system. We
show that an NMT model with over 200 million parameters can be pruned by 40%
with very little performance loss as measured on the WMT'14 English-German
translation task. This sheds light on the distribution of redundancy in the NMT
architecture. Our main result is that with retraining, we can recover and even
surpass the original performance with an 80%-pruned model.