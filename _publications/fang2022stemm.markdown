---
layout: publication
title: 'STEMM: Self-learning With Speech-text Manifold Mixup For Speech Translation'
authors: Qingkai Fang, Rong Ye, Lei Li, Yang Feng, Mingxuan Wang
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: fang2022stemm
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.10426'}]
tags: ["Evaluation"]
short_authors: Fang et al.
---
How to learn a better speech representation for end-to-end speech-to-text
translation (ST) with limited labeled data? Existing techniques often attempt
to transfer powerful machine translation (MT) capabilities to ST, but neglect
the representation discrepancy across modalities. In this paper, we propose the
Speech-TExt Manifold Mixup (STEMM) method to calibrate such discrepancy.
Specifically, we mix up the representation sequences of different modalities,
and take both unimodal speech sequences and multimodal mixed sequences as input
to the translation model in parallel, and regularize their output predictions
with a self-learning framework. Experiments on MuST-C speech translation
benchmark and further analysis show that our method effectively alleviates the
cross-modal representation discrepancy, and achieves significant improvements
over a strong baseline on eight translation directions.