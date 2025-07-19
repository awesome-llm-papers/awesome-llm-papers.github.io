---
layout: publication
title: An Empirical Exploration In Quality Filtering Of Text Data
authors: Gao Leo
conference: Molecular Ecology
year: 2021
bibkey: gao2021empirical
citations: 345
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.00698'}]
tags: [Training Techniques, GPT, Model Architecture, Fine Tuning, Datasets]
---
While conventional wisdom suggests that more aggressively filtering data from
low-quality sources like Common Crawl always monotonically improves the quality
of training data, we find that aggressive filtering can in fact lead to a
decrease in model quality on a wide array of downstream tasks for a GPT-like
language model. We speculate that this is because optimizing sufficiently
strongly for a proxy metric harms performance on the true objective, suggesting
a need for more robust filtering objectives when attempting to filter more
aggressively. We hope this work leads to detailed analysis of the effects of
dataset filtering design choices on downstream model performance in future
work.