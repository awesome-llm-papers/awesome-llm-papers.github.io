---
layout: publication
title: Partially Shuffling The Training Data To Improve Language Models
authors: Press Ofir
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2019
bibkey: press2019partially
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1903.04167'}]
tags: [Training Techniques, ACL, Datasets, Language Modeling, Alt]
---
Although SGD requires shuffling the training data between epochs, currently
none of the word-level language modeling systems do this. Naively shuffling all
sentences in the training data would not permit the model to learn
inter-sentence dependencies. Here we present a method that partially shuffles
the training data between epochs. This method makes each batch random, while
keeping most sentence ordering intact. It achieves new state of the art results
on word-level language modeling on both the Penn Treebank and WikiText-2
datasets.