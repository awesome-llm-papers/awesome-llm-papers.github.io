---
layout: publication
title: Lattice-based Transformer Encoder For Neural Machine Translation
authors: Xiao et al.
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: xiao2019lattice
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.01282'}]
tags: [Model Architecture, Training Techniques, ACL, Transformer, Attention Mechanism]
---
Neural machine translation (NMT) takes deterministic sequences for source
representations. However, either word-level or subword-level segmentations have
multiple choices to split a source sequence with different word segmentors or
different subword vocabulary sizes. We hypothesize that the diversity in
segmentations may affect the NMT performance. To integrate different
segmentations with the state-of-the-art NMT model, Transformer, we propose
lattice-based encoders to explore effective word or subword representation in
an automatic way during training. We propose two methods: 1) lattice positional
encoding and 2) lattice-aware self-attention. These two methods can be used
together and show complementary to each other to further improve translation
performance. Experiment results show superiorities of lattice-based encoders in
word-level and subword-level representations over conventional Transformer
encoder.