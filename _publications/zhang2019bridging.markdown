---
layout: publication
title: Bridging The Gap Between Training And Inference For Neural Machine Translation
authors: Wen Zhang, Yang Feng, Fandong Meng, di You, Qun Liu
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: zhang2019bridging
citations: 213
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.02448'}]
tags: ["Training Techniques"]
short_authors: Zhang et al.
---
Neural Machine Translation (NMT) generates target words sequentially in the
way of predicting the next word conditioned on the context words. At training
time, it predicts with the ground truth words as context while at inference it
has to generate the entire sequence from scratch. This discrepancy of the fed
context leads to error accumulation among the way. Furthermore, word-level
training requires strict matching between the generated sequence and the ground
truth sequence which leads to overcorrection over different but reasonable
translations. In this paper, we address these issues by sampling context words
not only from the ground truth sequence but also from the predicted sequence by
the model during training, where the predicted sequence is selected with a
sentence-level optimum. Experiment results on Chinese->English and WMT'14
English->German translation tasks demonstrate that our approach can achieve
significant improvements on multiple datasets.