---
layout: publication
title: Heterogeneous Encoders Scaling In The Transformer For Neural Machine Translation
authors: Hu et al.
conference: 'Proceedings of the Third Conference on Machine Translation: Research
  Papers'
year: 2023
bibkey: hu2023heterogeneous
citations: 139
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.15872'}]
tags: [Model Architecture, Transformer, WMT, Datasets, Reinforcement Learning, Attention
    Mechanism, Alt]
---
Although the Transformer is currently the best-performing architecture in the
homogeneous configuration (self-attention only) in Neural Machine Translation,
many State-of-the-Art models in Natural Language Processing are made of a
combination of different Deep Learning approaches. However, these models often
focus on combining a couple of techniques only and it is unclear why some
methods are chosen over others. In this work, we investigate the effectiveness
of integrating an increasing number of heterogeneous methods. Based on a simple
combination strategy and performance-driven synergy criteria, we designed the
Multi-Encoder Transformer, which consists of up to five diverse encoders.
Results showcased that our approach can improve the quality of the translation
across a variety of languages and dataset sizes and it is particularly
effective in low-resource languages where we observed a maximum increase of
7.16 BLEU compared to the single-encoder model.