---
layout: publication
title: Streaming Transformer-based Acoustic Models Using Self-attention With Augmented
  Memory
authors: Wu et al.
conference: Interspeech 2020
year: 2020
bibkey: wu2020streaming
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.08042'}]
tags: [Attention Mechanism, Evaluation, INTERSPEECH, Transformer, Model Architecture,
  Applications, Datasets]
---
Transformer-based acoustic modeling has achieved great suc-cess for both
hybrid and sequence-to-sequence speech recogni-tion. However, it requires
access to the full sequence, and thecomputational cost grows quadratically with
respect to the in-put sequence length. These factors limit its adoption for
stream-ing applications. In this work, we proposed a novel augmentedmemory
self-attention, which attends on a short segment of theinput sequence and a
bank of memories. The memory bankstores the embedding information for all the
processed seg-ments. On the librispeech benchmark, our proposed
methodoutperforms all the existing streamable transformer methods bya large
margin and achieved over 15% relative error reduction,compared with the widely
used LC-BLSTM baseline. Our find-ings are also confirmed on some large internal
datasets.