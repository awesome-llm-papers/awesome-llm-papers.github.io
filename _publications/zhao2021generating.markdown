---
layout: publication
title: Generating Natural Language Adversarial Examples Through An Improved Beam Search
  Algorithm
authors: Zhao et al.
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: zhao2021generating
citations: 340
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.08036'}]
tags: [EMNLP, Evaluation, BERT, Model Architecture, Efficiency And Optimization, Security,
  Datasets]
---
The research of adversarial attacks in the text domain attracts many
interests in the last few years, and many methods with a high attack success
rate have been proposed. However, these attack methods are inefficient as they
require lots of queries for the victim model when crafting text adversarial
examples. In this paper, a novel attack model is proposed, its attack success
rate surpasses the benchmark attack methods, but more importantly, its attack
efficiency is much higher than the benchmark attack methods. The novel method
is empirically evaluated by attacking WordCNN, LSTM, BiLSTM, and BERT on four
benchmark datasets. For instance, it achieves a 100% attack success rate
higher than the state-of-the-art method when attacking BERT and BiLSTM on IMDB,
but the number of queries for the victim models only is 1/4 and 1/6.5 of the
state-of-the-art method, respectively. Also, further experiments show the novel
method has a good transferability on the generated adversarial examples.