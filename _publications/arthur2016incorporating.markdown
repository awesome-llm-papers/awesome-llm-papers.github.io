---
layout: publication
title: Incorporating Discrete Translation Lexicons Into Neural Machine Translation
authors: Arthur Philip, Neubig Graham, Nakamura Satoshi
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: arthur2016incorporating
citations: 209
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.02006'}]
tags: [Model Architecture, Ethics And Bias, LLM For Code, EMNLP, Attention Mechanism]
---
Neural machine translation (NMT) often makes mistakes in translating
low-frequency content words that are essential to understanding the meaning of
the sentence. We propose a method to alleviate this problem by augmenting NMT
systems with discrete translation lexicons that efficiently encode translations
of these low-frequency words. We describe a method to calculate the lexicon
probability of the next word in the translation candidate by using the
attention vector of the NMT model to select which source word lexical
probabilities the model should focus on. We test two methods to combine this
probability with the standard NMT probability: (1) using it as a bias, and (2)
linear interpolation. Experiments on two corpora show an improvement of 2.0-2.3
BLEU and 0.13-0.44 NIST score, and faster convergence time.