---
layout: publication
title: Self-guided Contrastive Learning For BERT Sentence Representations
authors: Taeuk Kim, Kang Min Yoo, Sang-goo Lee
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: kim2021self
citations: 153
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.07345'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Taeuk Kim, Kang Min Yoo, Sang-goo Lee
---
Although BERT and its variants have reshaped the NLP landscape, it still
remains unclear how best to derive sentence embeddings from such pre-trained
Transformers. In this work, we propose a contrastive learning method that
utilizes self-guidance for improving the quality of BERT sentence
representations. Our method fine-tunes BERT in a self-supervised fashion, does
not rely on data augmentation, and enables the usual [CLS] token embeddings to
function as sentence vectors. Moreover, we redesign the contrastive learning
objective (NT-Xent) and apply it to sentence representation learning. We
demonstrate with extensive experiments that our approach is more effective than
competitive baselines on diverse sentence-related tasks. We also show it is
efficient at inference and robust to domain shifts.