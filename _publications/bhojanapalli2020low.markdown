---
layout: publication
title: Low-rank Bottleneck In Multi-head Attention Models
authors: Srinadh Bhojanapalli, Chulhee Yun, Ankit Singh Rawat, Sashank J. Reddi, Sanjiv
  Kumar
conference: Arxiv
year: 2020
citations: 15
bibkey: bhojanapalli2020low
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2002.07028'}]
tags: [Model Architecture, Attention Mechanism, Transformer, Pre-Training, Training
    Techniques]
---
Attention based Transformer architecture has enabled significant advances in
the field of natural language processing. In addition to new pre-training
techniques, recent improvements crucially rely on working with a relatively
larger embedding dimension for tokens. Unfortunately, this leads to models that
are prohibitively large to be employed in the downstream tasks. In this paper
we identify one of the important factors contributing to the large embedding
size requirement. In particular, our analysis highlights that the scaling
between the number of heads and the size of each head in the current
architecture gives rise to a low-rank bottleneck in attention heads, causing
this limitation. We further validate this in our experiments. As a solution we
propose to set the head size of an attention unit to input sequence length, and
independent of the number of heads, resulting in multi-head attention layers
with provably more expressive power. We empirically show that this allows us to
train models with a relatively smaller embedding dimension and with better
performance scaling.