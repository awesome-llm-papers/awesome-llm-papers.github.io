---
layout: publication
title: 'XGLUE: A New Benchmark Dataset For Cross-lingual Pre-training, Understanding
  And Generation'
authors: Yaobo Liang et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
citations: 50
bibkey: liang2020new
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.01401'}]
tags: [Model Architecture, Pre-Training, Training Techniques, BERT, Evaluation]
---
In this paper, we introduce XGLUE, a new benchmark dataset that can be used
to train large-scale cross-lingual pre-trained models using multilingual and
bilingual corpora and evaluate their performance across a diverse set of
cross-lingual tasks. Comparing to GLUE(Wang et al., 2019), which is labeled in
English for natural language understanding tasks only, XGLUE has two main
advantages: (1) it provides 11 diversified tasks that cover both natural
language understanding and generation scenarios; (2) for each task, it provides
labeled data in multiple languages. We extend a recent cross-lingual
pre-trained model Unicoder(Huang et al., 2019) to cover both understanding and
generation tasks, which is evaluated on XGLUE as a strong baseline. We also
evaluate the base versions (12-layer) of Multilingual BERT, XLM and XLM-R for
comparison.