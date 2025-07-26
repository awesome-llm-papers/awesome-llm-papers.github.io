---
layout: publication
title: Training Deeper Neural Machine Translation Models With Transparent Attention
authors: Ankur Bapna, Mia Xu Chen, Orhan Firat, Yuan Cao, Yonghui Wu
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: bapna2018training
citations: 145
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.07561'}]
tags: ["EMNLP", "Model Architecture", "Training Techniques"]
short_authors: Bapna et al.
---
While current state-of-the-art NMT models, such as RNN seq2seq and
Transformers, possess a large number of parameters, they are still shallow in
comparison to convolutional models used for both text and vision applications.
In this work we attempt to train significantly (2-3x) deeper Transformer and
Bi-RNN encoders for machine translation. We propose a simple modification to
the attention mechanism that eases the optimization of deeper models, and
results in consistent gains of 0.7-1.1 BLEU on the benchmark WMT'14
English-German and WMT'15 Czech-English tasks for both architectures.