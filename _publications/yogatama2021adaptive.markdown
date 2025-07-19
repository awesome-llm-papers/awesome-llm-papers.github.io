---
layout: publication
title: Adaptive Semiparametric Language Models
authors: Yogatama Dani, D'autume Cyprien de Masson, Kong Lingpeng
conference: Transactions of the Association for Computational Linguistics
year: 2021
bibkey: yogatama2021adaptive
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.02557'}]
tags: [Model Architecture, TACL, ACL, Transformer, Datasets, Language Modeling]
---
We present a language model that combines a large parametric neural network
(i.e., a transformer) with a non-parametric episodic memory component in an
integrated architecture. Our model uses extended short-term context by caching
local hidden states -- similar to transformer-XL -- and global long-term memory
by retrieving a set of nearest neighbor tokens at each timestep. We design a
gating function to adaptively combine multiple information sources to make a
prediction. This mechanism allows the model to use either local context,
short-term memory, or long-term memory (or any combination of them) on an ad
hoc basis depending on the context. Experiments on word-based and
character-based language modeling datasets demonstrate the efficacy of our
proposed method compared to strong baselines.