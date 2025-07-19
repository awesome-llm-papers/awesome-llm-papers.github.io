---
layout: publication
title: 'CPM: A Large-scale Generative Chinese Pre-trained Language Model'
authors: Zhang et al.
conference: AI Open
year: 2020
bibkey: zhang2020cpm
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.00413'}]
tags: [Training Techniques, Attention Mechanism, GPT, Model Architecture, Few Shot,
  Datasets]
---
Pre-trained Language Models (PLMs) have proven to be beneficial for various
downstream NLP tasks. Recently, GPT-3, with 175 billion parameters and 570GB
training data, drew a lot of attention due to the capacity of few-shot (even
zero-shot) learning. However, applying GPT-3 to address Chinese NLP tasks is
still challenging, as the training corpus of GPT-3 is primarily English, and
the parameters are not publicly available. In this technical report, we release
the Chinese Pre-trained Language Model (CPM) with generative pre-training on
large-scale Chinese training data. To the best of our knowledge, CPM, with 2.6
billion parameters and 100GB Chinese training data, is the largest Chinese
pre-trained language model, which could facilitate several downstream Chinese
NLP tasks, such as conversation, essay generation, cloze test, and language
understanding. Extensive experiments demonstrate that CPM achieves strong
performance on many NLP tasks in the settings of few-shot (even zero-shot)
learning. The code and parameters are available at
https://github.com/TsinghuaAI/CPM-Generate.