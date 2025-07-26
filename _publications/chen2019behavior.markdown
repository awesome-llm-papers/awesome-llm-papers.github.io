---
layout: publication
title: Behavior Sequence Transformer For E-commerce Recommendation In Alibaba
authors: Qiwei Chen, Huan Zhao, Wei Li, Pipei Huang, Wenwu Ou
conference: Proceedings of the 1st International Workshop on Deep Learning Practice
  for High-Dimensional Sparse Data
year: 2019
bibkey: chen2019behavior
citations: 325
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.06874'}]
tags: ["Model Architecture"]
short_authors: Chen et al.
---
Deep learning based methods have been widely used in industrial
recommendation systems (RSs). Previous works adopt an Embedding&MLP paradigm:
raw features are embedded into low-dimensional vectors, which are then fed on
to MLP for final recommendations. However, most of these works just concatenate
different features, ignoring the sequential nature of users' behaviors. In this
paper, we propose to use the powerful Transformer model to capture the
sequential signals underlying users' behavior sequences for recommendation in
Alibaba. Experimental results demonstrate the superiority of the proposed
model, which is then deployed online at Taobao and obtain significant
improvements in online Click-Through-Rate (CTR) comparing to two baselines.