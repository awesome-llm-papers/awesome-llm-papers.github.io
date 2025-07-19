---
layout: publication
title: Multi-task Learning For Multilingual Neural Machine Translation
authors: Wang Yiren, Zhai Chengxiang, Awadalla Hany Hassan
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: wang2020multi
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.02523'}]
tags: [RAG, EMNLP, Training Techniques, Tools, Fine Tuning, Datasets]
---
While monolingual data has been shown to be useful in improving bilingual
neural machine translation (NMT), effectively and efficiently leveraging
monolingual data for Multilingual NMT (MNMT) systems is a less explored area.
In this work, we propose a multi-task learning (MTL) framework that jointly
trains the model with the translation task on bitext data and two denoising
tasks on the monolingual data. We conduct extensive empirical studies on MNMT
systems with 10 language pairs from WMT datasets. We show that the proposed
approach can effectively improve the translation quality for both high-resource
and low-resource languages with large margin, achieving significantly better
results than the individual bilingual models. We also demonstrate the efficacy
of the proposed approach in the zero-shot setup for language pairs without
bitext training data. Furthermore, we show the effectiveness of MTL over
pre-training approaches for both NMT and cross-lingual transfer learning NLU
tasks; the proposed approach outperforms massive scale models trained on single
task.