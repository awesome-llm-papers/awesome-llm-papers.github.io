---
layout: publication
title: Insertion-based Decoding With Automatically Inferred Generation Order
authors: Jiatao Gu, Qi Liu, Kyunghyun Cho
conference: Transactions of the Association for Computational Linguistics
year: 2019
bibkey: gu2019insertion
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.01370'}]
tags: ["TACL"]
short_authors: Jiatao Gu, Qi Liu, Kyunghyun Cho
---
Conventional neural autoregressive decoding commonly assumes a fixed
left-to-right generation order, which may be sub-optimal. In this work, we
propose a novel decoding algorithm -- InDIGO -- which supports flexible
sequence generation in arbitrary orders through insertion operations. We extend
Transformer, a state-of-the-art sequence generation model, to efficiently
implement the proposed approach, enabling it to be trained with either a
pre-defined generation order or adaptive orders obtained from beam-search.
Experiments on four real-world tasks, including word order recovery, machine
translation, image caption and code generation, demonstrate that our algorithm
can generate sequences following arbitrary orders, while achieving competitive
or even better performance compared to the conventional left-to-right
generation. The generated sequences show that InDIGO adopts adaptive generation
orders based on input information.