---
layout: publication
title: An Empirical Survey Of Data Augmentation For Limited Data Learning In NLP
authors: Jiaao Chen, Derek Tam, Colin Raffel, Mohit Bansal, Diyi Yang
conference: Transactions of the Association for Computational Linguistics
year: 2023
bibkey: chen2021empirical
citations: 101
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.07499'}]
tags: ["Datasets", "Survey Paper", "TACL"]
short_authors: Chen et al.
---
NLP has achieved great progress in the past decade through the use of neural
models and large labeled datasets. The dependence on abundant data prevents NLP
models from being applied to low-resource settings or novel tasks where
significant time, money, or expertise is required to label massive amounts of
textual data. Recently, data augmentation methods have been explored as a means
of improving data efficiency in NLP. To date, there has been no systematic
empirical overview of data augmentation for NLP in the limited labeled data
setting, making it difficult to understand which methods work in which
settings. In this paper, we provide an empirical survey of recent progress on
data augmentation for NLP in the limited labeled data setting, summarizing the
landscape of methods (including token-level augmentations, sentence-level
augmentations, adversarial augmentations, and hidden-space augmentations) and
carrying out experiments on 11 datasets covering topics/news classification,
inference tasks, paraphrasing tasks, and single-sentence tasks. Based on the
results, we draw several conclusions to help practitioners choose appropriate
augmentations in different settings and discuss the current challenges and
future directions for limited data learning in NLP.