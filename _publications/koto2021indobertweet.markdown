---
layout: publication
title: 'Indobertweet: A Pretrained Language Model For Indonesian Twitter With Effective
  Domain-specific Vocabulary Initialization'
authors: Koto Fajri, Lau Jey Han, Baldwin Timothy
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: koto2021indobertweet
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.04607'}]
tags: [RAG, EMNLP, Training Techniques, Evaluation, BERT, Model Architecture, Datasets]
---
We present IndoBERTweet, the first large-scale pretrained model for
Indonesian Twitter that is trained by extending a monolingually-trained
Indonesian BERT model with additive domain-specific vocabulary. We focus in
particular on efficient model adaptation under vocabulary mismatch, and
benchmark different ways of initializing the BERT embedding layer for new word
types. We find that initializing with the average BERT subword embedding makes
pretraining five times faster, and is more effective than proposed methods for
vocabulary adaptation in terms of extrinsic evaluation over seven Twitter-based
datasets.