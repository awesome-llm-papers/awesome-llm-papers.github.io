---
layout: publication
title: Developing RNN-T Models Surpassing High-performance Hybrid Models With Customization
  Capability
authors: Jinyu Li, Rui Zhao, Zhong Meng, Yanqing Liu, Wenning Wei, Sarangarajan Parthasarathy,
  Vadim Mazalov, Zhenghao Wang, Lei He, Sheng Zhao, Yifan Gong
conference: Interspeech 2020
year: 2020
bibkey: li2020developing
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.15188'}]
tags: ["INTERSPEECH", "Training Techniques"]
short_authors: Li et al.
---
Because of its streaming nature, recurrent neural network transducer (RNN-T)
is a very promising end-to-end (E2E) model that may replace the popular hybrid
model for automatic speech recognition. In this paper, we describe our recent
development of RNN-T models with reduced GPU memory consumption during
training, better initialization strategy, and advanced encoder modeling with
future lookahead. When trained with Microsoft's 65 thousand hours of anonymized
training data, the developed RNN-T model surpasses a very well trained hybrid
model with both better recognition accuracy and lower latency. We further study
how to customize RNN-T models to a new domain, which is important for deploying
E2E models to practical scenarios. By comparing several methods leveraging
text-only data in the new domain, we found that updating RNN-T's prediction and
joint networks using text-to-speech generated from domain-specific text is the
most effective.