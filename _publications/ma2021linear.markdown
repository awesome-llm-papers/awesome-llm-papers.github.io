---
layout: publication
title: 'Luna: Linear Unified Nested Attention'
authors: Xuezhe Ma et al.
conference: Arxiv
year: 2021
citations: 48
bibkey: ma2021linear
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.01540'}]
tags: [Training Techniques, Transformer, Attention Mechanism, Reinforcement Learning,
  Efficiency and Optimization, Model Architecture]
---
The quadratic computational and memory complexities of the Transformer's
attention mechanism have limited its scalability for modeling long sequences.
In this paper, we propose Luna, a linear unified nested attention mechanism
that approximates softmax attention with two nested linear attention functions,
yielding only linear (as opposed to quadratic) time and space complexity.
Specifically, with the first attention function, Luna packs the input sequence
into a sequence of fixed length. Then, the packed sequence is unpacked using
the second attention function. As compared to a more traditional attention
mechanism, Luna introduces an additional sequence with a fixed length as input
and an additional corresponding output, which allows Luna to perform attention
operation linearly, while also storing adequate contextual information. We
perform extensive evaluations on three benchmarks of sequence modeling tasks:
long-context sequence modeling, neural machine translation and masked language
modeling for large-scale pretraining. Competitive or even better experimental
results demonstrate both the effectiveness and efficiency of Luna compared to a
variety