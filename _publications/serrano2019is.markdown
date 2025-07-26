---
layout: publication
title: Is Attention Interpretable?
authors: Sofia Serrano, Noah A. Smith
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: serrano2019is
citations: 493
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.03731'}]
tags: ["Model Architecture"]
short_authors: Sofia Serrano, Noah A. Smith
---
Attention mechanisms have recently boosted performance on a range of NLP
tasks. Because attention layers explicitly weight input components'
representations, it is also often assumed that attention can be used to
identify information that models found important (e.g., specific contextualized
word tokens). We test whether that assumption holds by manipulating attention
weights in already-trained text classification models and analyzing the
resulting differences in their predictions. While we observe some ways in which
higher attention weights correlate with greater impact on model predictions, we
also find many ways in which this does not hold, i.e., where gradient-based
rankings of attention weights better predict their effects than their
magnitudes. We conclude that while attention noisily predicts input components'
overall importance to a model, it is by no means a fail-safe indicator.