---
layout: publication
title: Deep Unknown Intent Detection With Margin Loss
authors: Ting-en Lin, Hua Xu
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: lin2019deep
citations: 138
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.00434'}]
tags: ["Training Techniques"]
short_authors: Ting-en Lin, Hua Xu
---
Identifying the unknown (novel) user intents that have never appeared in the
training set is a challenging task in the dialogue system. In this paper, we
present a two-stage method for detecting unknown intents. We use bidirectional
long short-term memory (BiLSTM) network with the margin loss as the feature
extractor. With margin loss, we can learn discriminative deep features by
forcing the network to maximize inter-class variance and to minimize
intra-class variance. Then, we feed the feature vectors to the density-based
novelty detection algorithm, local outlier factor (LOF), to detect unknown
intents. Experiments on two benchmark datasets show that our method can yield
consistent improvements compared with the baseline methods.