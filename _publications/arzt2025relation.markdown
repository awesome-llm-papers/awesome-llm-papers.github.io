---
layout: publication
title: Relation Extraction Or Pattern Matching? Unravelling The Generalisation Limits
  Of Language Models For Biographical RE
authors: Arzt et al.
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2025
bibkey: arzt2025relation
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.12533'}]
tags: [Training Techniques, EMNLP, Evaluation, In Context Learning, Few Shot, Fine
    Tuning, Datasets]
---
Analysing the generalisation capabilities of relation extraction (RE) models is crucial for assessing whether they learn robust relational patterns or rely on spurious correlations. Our cross-dataset experiments find that RE models struggle with unseen data, even within similar domains. Notably, higher intra-dataset performance does not indicate better transferability, instead often signaling overfitting to dataset-specific artefacts. Our results also show that data quality, rather than lexical similarity, is key to robust transfer, and the choice of optimal adaptation strategy depends on the quality of data available: while fine-tuning yields the best cross-dataset performance with high-quality data, few-shot in-context learning (ICL) is more effective with noisier data. However, even in these cases, zero-shot baselines occasionally outperform all cross-dataset results. Structural issues in RE benchmarks, such as single-relation per sample constraints and non-standardised negative class definitions, further hinder model transferability.