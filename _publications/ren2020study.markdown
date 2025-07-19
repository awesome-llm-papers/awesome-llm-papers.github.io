---
layout: publication
title: A Study Of Non-autoregressive Model For Sequence Generation
authors: Ren et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: ren2020study
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.10454'}]
tags: [Distillation, Training Techniques, Efficiency And Optimization, ACL, RAG, GPT,
  Language Modeling]
---
Non-autoregressive (NAR) models generate all the tokens of a sequence in
parallel, resulting in faster generation speed compared to their autoregressive
(AR) counterparts but at the cost of lower accuracy. Different techniques
including knowledge distillation and source-target alignment have been proposed
to bridge the gap between AR and NAR models in various tasks such as neural
machine translation (NMT), automatic speech recognition (ASR), and text to
speech (TTS). With the help of those techniques, NAR models can catch up with
the accuracy of AR models in some tasks but not in some others. In this work,
we conduct a study to understand the difficulty of NAR sequence generation and
try to answer: (1) Why NAR models can catch up with AR models in some tasks but
not all? (2) Why techniques like knowledge distillation and source-target
alignment can help NAR models. Since the main difference between AR and NAR
models is that NAR models do not use dependency among target tokens while AR
models do, intuitively the difficulty of NAR sequence generation heavily
depends on the strongness of dependency among target tokens. To quantify such
dependency, we propose an analysis model called CoMMA to characterize the
difficulty of different NAR sequence generation tasks. We have several
interesting findings: 1) Among the NMT, ASR and TTS tasks, ASR has the most
target-token dependency while TTS has the least. 2) Knowledge distillation
reduces the target-token dependency in target sequence and thus improves the
accuracy of NAR models. 3) Source-target alignment constraint encourages
dependency of a target token on source tokens and thus eases the training of
NAR models.