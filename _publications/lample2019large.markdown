---
layout: publication
title: Large Memory Layers With Product Keys
authors: Lample et al.
conference: Arxiv
year: 2019
bibkey: lample2019large
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1907.05242'}]
tags: [Training Techniques, Transformer, Model Architecture, Efficiency And Optimization,
  Language Modeling, Datasets]
---
This paper introduces a structured memory which can be easily integrated into
a neural network. The memory is very large by design and significantly
increases the capacity of the architecture, by up to a billion parameters with
a negligible computational overhead. Its design and access pattern is based on
product keys, which enable fast and exact nearest neighbor search. The ability
to increase the number of parameters while keeping the same computational
budget lets the overall system strike a better trade-off between prediction
accuracy and computation efficiency both at training and test time. This memory
layer allows us to tackle very large scale language modeling tasks. In our
experiments we consider a dataset with up to 30 billion words, and we plug our
memory layer in a state-of-the-art transformer-based architecture. In
particular, we found that a memory augmented model with only 12 layers
outperforms a baseline transformer model with 24 layers, while being twice
faster at inference time. We release our code for reproducibility purposes.