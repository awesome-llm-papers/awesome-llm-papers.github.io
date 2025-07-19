---
layout: publication
title: Neural Attention Search
authors: Deng Difan, Lindauer Marius
conference: Cerebral Cortex
year: 2025
bibkey: deng2025neural
citations: 430
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.13251'}]
tags: [Training Techniques, Attention Mechanism, Tools, Transformer, Model Architecture,
  Fine Tuning]
---
We present Neural Attention Search (NAtS), a framework that automatically
evaluates the importance of each token within a sequence and determines if the
corresponding token can be dropped after several steps. This approach can
efficiently reduce the KV cache sizes required by transformer-based models
during inference and thus reduce inference costs. In this paper, we design a
search space that contains three token types: (i) Global Tokens will be
preserved and queried by all the following tokens. (ii) Local Tokens survive
until the next global token appears. (iii) Sliding Window Tokens have an impact
on the inference of a fixed size of the next following tokens. Similar to the
One-Shot Neural Architecture Search approach, this token-type information can
be learned jointly with the architecture weights via a learnable attention
mask. Experiments on both training a new transformer from scratch and
fine-tuning existing large language models show that NAtS can efficiently
reduce the KV cache size required for the models while maintaining the models'
performance.