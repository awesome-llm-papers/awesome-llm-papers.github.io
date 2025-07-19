---
layout: publication
title: Improving Massively Multilingual Neural Machine Translation And Zero-shot Translation
authors: Zhang et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: zhang2020improving
citations: 201
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.11867'}]
tags: [Model Architecture, Training Techniques, ACL, Datasets, Reinforcement Learning]
---
Massively multilingual models for neural machine translation (NMT) are
theoretically attractive, but often underperform bilingual models and deliver
poor zero-shot translations. In this paper, we explore ways to improve them. We
argue that multilingual NMT requires stronger modeling capacity to support
language pairs with varying typological characteristics, and overcome this
bottleneck via language-specific components and deepening NMT architectures. We
identify the off-target translation issue (i.e. translating into a wrong target
language) as the major source of the inferior zero-shot performance, and
propose random online backtranslation to enforce the translation of unseen
training language pairs. Experiments on OPUS-100 (a novel multilingual dataset
with 100 languages) show that our approach substantially narrows the
performance gap with bilingual models in both one-to-many and many-to-many
settings, and improves zero-shot performance by ~10 BLEU, approaching
conventional pivot-based methods.