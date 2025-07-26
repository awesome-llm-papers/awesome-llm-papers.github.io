---
layout: publication
title: 'Cosda-ml: Multi-lingual Code-switching Data Augmentation For Zero-shot Cross-lingual
  NLP'
authors: Libo Qin, Minheng Ni, Yue Zhang, Wanxiang Che
conference: Proceedings of the Twenty-Ninth International Joint Conference on Artificial
  Intelligence
year: 2020
bibkey: qin2020cosda
citations: 118
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.06402'}]
tags: ["IJCAI"]
short_authors: Qin et al.
---
Multi-lingual contextualized embeddings, such as multilingual-BERT (mBERT),
have shown success in a variety of zero-shot cross-lingual tasks. However,
these models are limited by having inconsistent contextualized representations
of subwords across different languages. Existing work addresses this issue by
bilingual projection and fine-tuning technique. We propose a data augmentation
framework to generate multi-lingual code-switching data to fine-tune mBERT,
which encourages model to align representations from source and multiple target
languages once by mixing their context information. Compared with the existing
work, our method does not rely on bilingual sentences for training, and
requires only one training process for multiple target languages. Experimental
results on five tasks with 19 languages show that our method leads to
significantly improved performances for all the tasks compared with mBERT.