---
layout: publication
title: Augmenting Self-attention With Persistent Memory
authors: Sukhbaatar et al.
conference: Arxiv
year: 2019
bibkey: sukhbaatar2019augmenting
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1907.01470'}]
tags: [Attention Mechanism, Evaluation, Transformer, Model Architecture, Language
    Modeling, Datasets]
---
Transformer networks have lead to important progress in language modeling and
machine translation. These models include two consecutive modules, a
feed-forward layer and a self-attention layer. The latter allows the network to
capture long term dependencies and are often regarded as the key ingredient in
the success of Transformers. Building upon this intuition, we propose a new
model that solely consists of attention layers. More precisely, we augment the
self-attention layers with persistent memory vectors that play a similar role
as the feed-forward layer. Thanks to these vectors, we can remove the
feed-forward layer without degrading the performance of a transformer. Our
evaluation shows the benefits brought by our model on standard character and
word level language modeling benchmarks.