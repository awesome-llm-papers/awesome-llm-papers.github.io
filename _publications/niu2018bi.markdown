---
layout: publication
title: Bi-directional Differentiable Input Reconstruction For Low-resource Neural
  Machine Translation
authors: Xing Niu, Weijia Xu, Marine Carpuat
conference: Proceedings of the 2nd Workshop on Neural Machine Translation and Generation
year: 2018
bibkey: niu2018bi
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.01116'}]
tags: []
short_authors: Xing Niu, Weijia Xu, Marine Carpuat
---
We aim to better exploit the limited amounts of parallel text available in
low-resource settings by introducing a differentiable reconstruction loss for
neural machine translation (NMT). This loss compares original inputs to
reconstructed inputs, obtained by back-translating translation hypotheses into
the input language. We leverage differentiable sampling and bi-directional NMT
to train models end-to-end, without introducing additional parameters. This
approach achieves small but consistent BLEU improvements on four language pairs
in both translation directions, and outperforms an alternative differentiable
reconstruction strategy based on hidden states.