---
layout: publication
title: 'Terapipe: Token-level Pipeline Parallelism For Training Large-scale Language
  Models'
authors: Zhuohan Li et al.
conference: Arxiv
year: 2021
citations: 26
bibkey: li2021token
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.07988'}, {name: Code,
    url: 'https://github.com/zhuohan123/terapipe'}]
tags: [Has Code, Model Architecture, GPT, Transformer, Tools, Training Techniques]
---
Model parallelism has become a necessity for training modern large-scale deep
language models. In this work, we identify a new and orthogonal dimension from
existing model parallel approaches: it is possible to perform pipeline
parallelism within a single training sequence for Transformer-based language
models thanks to its autoregressive property. This enables a more fine-grained
pipeline compared with previous work. With this key idea, we design TeraPipe, a
high-performance token-level pipeline parallel algorithm for synchronous
model-parallel training of Transformer-based language models. We develop a
novel dynamic programming-based algorithm to calculate the optimal pipelining
execution scheme given a specific model and cluster configuration. We show that
TeraPipe can speed up the training by 5.0x for the largest GPT-3 model with 175
billion parameters on an AWS cluster with 48 p3.16xlarge instances compared
with state-of-the-art model-parallel methods. The code for reproduction can be
found at https://github.com/zhuohan123/terapipe