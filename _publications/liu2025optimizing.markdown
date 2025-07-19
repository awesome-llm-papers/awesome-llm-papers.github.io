---
layout: publication
title: 'Optimizing Sentence Embedding With Pseudo-labeling And Model Ensembles: A
  Hierarchical Framework For Enhanced NLP Tasks'
authors: Liu Ziwei, Zhang Qi, Gao Lifu
conference: 2020 25th International Conference on Pattern Recognition (ICPR)
year: 2025
bibkey: liu2025optimizing
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.15876'}]
tags: [Training Techniques, Attention Mechanism, Tools, BERT, Model Architecture,
  Datasets, Merging]
---
Sentence embedding tasks are important in natural language processing (NLP),
but improving their performance while keeping them reliable is still hard. This
paper presents a framework that combines pseudo-label generation and model
ensemble techniques to improve sentence embeddings. We use external data from
SimpleWiki, Wikipedia, and BookCorpus to make sure the training data is
consistent. The framework includes a hierarchical model with an encoding layer,
refinement layer, and ensemble prediction layer, using ALBERT-xxlarge,
RoBERTa-large, and DeBERTa-large models. Cross-attention layers combine
external context, and data augmentation techniques like synonym replacement and
back-translation increase data variety. Experimental results show large
improvements in accuracy and F1-score compared to basic models, and studies
confirm that cross-attention and data augmentation make a difference. This work
presents an effective way to improve sentence embedding tasks and lays the
groundwork for future NLP research.