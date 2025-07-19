---
layout: publication
title: 'Totto: A Controlled Table-to-text Generation Dataset'
authors: Parikh et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: parikh2020totto
citations: 176
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.14373'}]
tags: [Training Techniques, EMNLP, Evaluation, Language Modeling, Reinforcement Learning,
  Datasets]
---
We present ToTTo, an open-domain English table-to-text dataset with over
120,000 training examples that proposes a controlled generation task: given a
Wikipedia table and a set of highlighted table cells, produce a one-sentence
description. To obtain generated targets that are natural but also faithful to
the source table, we introduce a dataset construction process where annotators
directly revise existing candidate sentences from Wikipedia. We present
systematic analyses of our dataset and annotation process as well as results
achieved by several state-of-the-art baselines. While usually fluent, existing
methods often hallucinate phrases that are not supported by the table,
suggesting that this dataset can serve as a useful research benchmark for
high-precision conditional text generation.