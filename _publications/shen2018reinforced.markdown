---
layout: publication
title: 'Reinforced Self-attention Network: A Hybrid Of Hard And Soft Attention For
  Sequence Modeling'
authors: Shen et al.
conference: Proceedings of the Twenty-Seventh International Joint Conference on Artificial
  Intelligence
year: 2018
bibkey: shen2018reinforced
citations: 133
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1801.10296'}]
tags: [Model Architecture, Merging, Training Techniques, RSS, Time Series, AAAI, Transformer,
  IJCAI, Datasets, Reinforcement Learning, Attention Mechanism]
---
Many natural language processing tasks solely rely on sparse dependencies
between a few tokens in a sentence. Soft attention mechanisms show promising
performance in modeling local/global dependencies by soft probabilities between
every two tokens, but they are not effective and efficient when applied to long
sentences. By contrast, hard attention mechanisms directly select a subset of
tokens but are difficult and inefficient to train due to their combinatorial
nature. In this paper, we integrate both soft and hard attention into one
context fusion model, "reinforced self-attention (ReSA)", for the mutual
benefit of each other. In ReSA, a hard attention trims a sequence for a soft
self-attention to process, while the soft attention feeds reward signals back
to facilitate the training of the hard one. For this purpose, we develop a
novel hard attention called "reinforced sequence sampling (RSS)", selecting
tokens in parallel and trained via policy gradient. Using two RSS modules, ReSA
efficiently extracts the sparse dependencies between each pair of selected
tokens. We finally propose an RNN/CNN-free sentence-encoding model, "reinforced
self-attention network (ReSAN)", solely based on ReSA. It achieves
state-of-the-art performance on both Stanford Natural Language Inference (SNLI)
and Sentences Involving Compositional Knowledge (SICK) datasets.