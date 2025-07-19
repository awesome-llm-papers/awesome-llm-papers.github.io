---
layout: publication
title: 'Promda: Prompt-based Data Augmentation For Low-resource NLU Tasks'
authors: Wang et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: wang2022promda
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.12499'}]
tags: [Prompting, Training Techniques, Evaluation, ACL, Datasets]
---
This paper focuses on the Data Augmentation for low-resource Natural Language
Understanding (NLU) tasks. We propose Prompt-based D\}ata Augmentation model
(PromDA) which only trains small-scale Soft Prompt (i.e., a set of trainable
vectors) in the frozen Pre-trained Language Models (PLMs). This avoids human
effort in collecting unlabeled in-domain data and maintains the quality of
generated synthetic data. In addition, PromDA generates synthetic data via two
different views and filters out the low-quality data using NLU models.
Experiments on four benchmarks show that synthetic data produced by PromDA
successfully boost up the performance of NLU models which consistently
outperform several competitive baseline models, including a state-of-the-art
semi-supervised model using unlabeled in-domain data. The synthetic data from
PromDA are also complementary with unlabeled in-domain data. The NLU models can
be further improved when they are combined for training.