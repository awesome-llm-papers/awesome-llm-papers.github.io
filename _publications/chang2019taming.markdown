---
layout: publication
title: Taming Pretrained Transformers For Extreme Multi-label Text Classification
authors: Wei-cheng Chang, Hsiang-fu Yu, Kai Zhong, Yiming Yang, Inderjit Dhillon
conference: Proceedings of the 26th ACM SIGKDD International Conference on Knowledge
  Discovery &amp; Data Mining
year: 2020
bibkey: chang2019taming
citations: 191
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.02331'}]
tags: ["Fine-Tuning", "KDD", "Model Architecture", "Training Techniques"]
short_authors: Chang et al.
---
We consider the extreme multi-label text classification (XMC) problem: given
an input text, return the most relevant labels from a large label collection.
For example, the input text could be a product description on Amazon.com and
the labels could be product categories. XMC is an important yet challenging
problem in the NLP community. Recently, deep pretrained transformer models have
achieved state-of-the-art performance on many NLP tasks including sentence
classification, albeit with small label sets. However, naively applying deep
transformer models to the XMC problem leads to sub-optimal performance due to
the large output space and the label sparsity issue. In this paper, we propose
X-Transformer, the first scalable approach to fine-tuning deep transformer
models for the XMC problem. The proposed method achieves new state-of-the-art
results on four XMC benchmark datasets. In particular, on a Wiki dataset with
around 0.5 million labels, the prec@1 of X-Transformer is 77.28%, a substantial
improvement over state-of-the-art XMC approaches Parabel (linear) and
AttentionXML (neural), which achieve 68.70% and 76.95% precision@1,
respectively. We further apply X-Transformer to a product2query dataset from
Amazon and gained 10.7% relative improvement on prec@1 over Parabel.