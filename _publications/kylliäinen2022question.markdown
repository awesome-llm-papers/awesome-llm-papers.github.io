---
layout: publication
title: Question Answering And Question Generation For Finnish
authors: "Kylli\xE4inen Ilmari, Yangarber Roman"
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2022
bibkey: "kylli\xE4inen2022question"
citations: 101
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.13794'}]
tags: [Model Architecture, Training Techniques, Fine Tuning, Evaluation, EMNLP, Transformer,
  Datasets, Language Modeling]
---
Recent advances in the field of language modeling have improved the
state-of-the-art in question answering (QA) and question generation (QG).
However, the development of modern neural models, their benchmarks, and
datasets for training them has mainly focused on English. Finnish, like many
other languages, faces a shortage of large QA/QG model training resources,
which has prevented experimenting with state-of-the-art QA/QG fine-tuning
methods. We present the first neural QA and QG models that work with Finnish.
To train the models, we automatically translate the SQuAD dataset and then use
normalization methods to reduce the amount of problematic data created during
the translation. Using the synthetic data, together with the Finnish partition
of the TyDi-QA dataset, we fine-tune several transformer-based models to both
QA and QG and evaluate their performance. To the best of our knowledge, the
resulting dataset is the first large-scale QA/QG resource for Finnish. This
paper also sets the initial benchmarks for Finnish-language QA and QG.