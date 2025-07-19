---
layout: publication
title: 'Rethinking Self-attention: Towards Interpretability In Neural Parsing'
authors: Mrini et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2019
bibkey: mrini2019rethinking
citations: 107
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.03875'}]
tags: [Model Architecture, Interpretability And Explainability, ACL, EMNLP, Transformer,
  Attention Mechanism]
---
Attention mechanisms have improved the performance of NLP tasks while
allowing models to remain explainable. Self-attention is currently widely used,
however interpretability is difficult due to the numerous attention
distributions. Recent work has shown that model representations can benefit
from label-specific information, while facilitating interpretation of
predictions. We introduce the Label Attention Layer: a new form of
self-attention where attention heads represent labels. We test our novel layer
by running constituency and dependency parsing experiments and show our new
model obtains new state-of-the-art results for both tasks on both the Penn
Treebank (PTB) and Chinese Treebank. Additionally, our model requires fewer
self-attention layers compared to existing work. Finally, we find that the
Label Attention heads learn relations between syntactic categories and show
pathways to analyze errors.