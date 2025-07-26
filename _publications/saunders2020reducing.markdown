---
layout: publication
title: Reducing Gender Bias In Neural Machine Translation As A Domain Adaptation Problem
authors: Danielle Saunders, Bill Byrne
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: saunders2020reducing
citations: 107
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.04498'}]
tags: ["Ethics & Fairness"]
short_authors: Danielle Saunders, Bill Byrne
---
Training data for NLP tasks often exhibits gender bias in that fewer
sentences refer to women than to men. In Neural Machine Translation (NMT)
gender bias has been shown to reduce translation quality, particularly when the
target language has grammatical gender. The recent WinoMT challenge set allows
us to measure this effect directly (Stanovsky et al, 2019).
  Ideally we would reduce system bias by simply debiasing all data prior to
training, but achieving this effectively is itself a challenge. Rather than
attempt to create a `balanced' dataset, we use transfer learning on a small set
of trusted, gender-balanced examples. This approach gives strong and consistent
improvements in gender debiasing with much less computational cost than
training from scratch.
  A known pitfall of transfer learning on new domains is `catastrophic
forgetting', which we address both in adaptation and in inference. During
adaptation we show that Elastic Weight Consolidation allows a performance
trade-off between general translation quality and bias reduction. During
inference we propose a lattice-rescoring scheme which outperforms all systems
evaluated in Stanovsky et al (2019) on WinoMT with no degradation of general
test set BLEU, and we show this scheme can be applied to remove gender bias in
the output of `black box` online commercial MT systems. We demonstrate our
approach translating from English into three languages with varied linguistic
properties and data availability.