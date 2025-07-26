---
layout: publication
title: 'Realformer: Transformer Likes Residual Attention'
authors: Ruining He, Anirudh Ravula, Bhargav Kanagal, Joshua Ainslie
conference: 'Findings of the Association for Computational Linguistics: ACL-IJCNLP
  2021'
year: 2021
bibkey: he2020realformer
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.11747'}]
tags: ["Has Code", "Model Architecture"]
short_authors: He et al.
---
Transformer is the backbone of modern NLP models. In this paper, we propose
RealFormer, a simple and generic technique to create Residual Attention Layer
Transformer networks that significantly outperform the canonical Transformer
and its variants (BERT, ETC, etc.) on a wide spectrum of tasks including Masked
Language Modeling, GLUE, SQuAD, Neural Machine Translation, WikiHop, HotpotQA,
Natural Questions, and OpenKP. We also observe empirically that RealFormer
stabilizes training and leads to models with sparser attention. Source code and
pre-trained checkpoints for RealFormer can be found at
https://github.com/google-research/google-research/tree/master/realformer.