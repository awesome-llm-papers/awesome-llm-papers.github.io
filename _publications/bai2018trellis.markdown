---
layout: publication
title: Trellis Networks For Sequence Modeling
authors: Shaojie Bai, J. Zico Kolter, Vladlen Koltun
conference: Arxiv
year: 2018
bibkey: bai2018trellis
citations: 70
additional_links: [{name: Code, url: 'https://github.com/locuslab/trellisnet'}, {
    name: Paper, url: 'https://arxiv.org/abs/1810.06682'}]
tags: ["Has Code", "Model Architecture"]
short_authors: Shaojie Bai, J. Zico Kolter, Vladlen Koltun
---
We present trellis networks, a new architecture for sequence modeling. On the
one hand, a trellis network is a temporal convolutional network with special
structure, characterized by weight tying across depth and direct injection of
the input into deep layers. On the other hand, we show that truncated recurrent
networks are equivalent to trellis networks with special sparsity structure in
their weight matrices. Thus trellis networks with general weight matrices
generalize truncated recurrent networks. We leverage these connections to
design high-performing trellis networks that absorb structural and algorithmic
elements from both recurrent and convolutional models. Experiments demonstrate
that trellis networks outperform the current state of the art methods on a
variety of challenging benchmarks, including word-level language modeling and
character-level language modeling tasks, and stress tests designed to evaluate
long-term memory retention. The code is available at
https://github.com/locuslab/trellisnet .