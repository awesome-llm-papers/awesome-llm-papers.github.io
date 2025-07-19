---
layout: publication
title: Gradient-based Adversarial Attacks Against Text Transformers
authors: Guo et al.
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: guo2021gradient
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.13733'}]
tags: [EMNLP, Transformer, Model Architecture, Efficiency And Optimization, Security]
---
We propose the first general-purpose gradient-based attack against
transformer models. Instead of searching for a single adversarial example, we
search for a distribution of adversarial examples parameterized by a
continuous-valued matrix, hence enabling gradient-based optimization. We
empirically demonstrate that our white-box attack attains state-of-the-art
attack performance on a variety of natural language tasks. Furthermore, we show
that a powerful black-box transfer attack, enabled by sampling from the
adversarial distribution, matches or exceeds existing methods, while only
requiring hard-label outputs.