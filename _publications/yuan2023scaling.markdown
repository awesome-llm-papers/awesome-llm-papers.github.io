---
layout: publication
title: Scaling Relationship On Learning Mathematical Reasoning With Large Language
  Models
authors: Yuan et al.
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 5: Industry Track)'
year: 2023
bibkey: yuan2023scaling
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.01825'}]
tags: [Datasets, Fine Tuning, ACL, Training Techniques]
---
Mathematical reasoning is a challenging task for large language models
(LLMs), while the scaling relationship of it with respect to LLM capacity is
under-explored. In this paper, we investigate how the pre-training loss,
supervised data amount, and augmented data amount influence the reasoning
performances of a supervised LLM. We find that pre-training loss is a better
indicator of the model's performance than the model's parameter count. We apply
supervised fine-tuning (SFT) with different amounts of supervised data and
empirically find a log-linear relation between data amount and model
performance, and we find better models improve less with enlarged supervised
datasets. To augment more data samples for improving model performances without
any human effort, we propose to apply Rejection sampling Fine-Tuning (RFT). RFT
uses supervised models to generate and collect correct reasoning paths as
augmented fine-tuning datasets. We find with augmented samples containing more
distinct reasoning paths, RFT improves mathematical reasoning performance more
for LLMs. We also find RFT brings more improvement for less performant LLMs.
Furthermore, we combine rejection samples from multiple models which push
LLaMA-7B to an accuracy of 49.3% on GSM8K which outperforms the supervised
fine-tuning (SFT) accuracy of 35.9% significantly.