---
layout: publication
title: Convolutional Sequence To Sequence Learning
authors: Jonas Gehring, Michael Auli, David Grangier, Denis Yarats, Yann N. Dauphin
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: gehring2017convolutional
citations: 434
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1705.03122'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Gehring et al.
---
The prevalent approach to sequence to sequence learning maps an input
sequence to a variable length output sequence via recurrent neural networks. We
introduce an architecture based entirely on convolutional neural networks.
Compared to recurrent models, computations over all elements can be fully
parallelized during training and optimization is easier since the number of
non-linearities is fixed and independent of the input length. Our use of gated
linear units eases gradient propagation and we equip each decoder layer with a
separate attention module. We outperform the accuracy of the deep LSTM setup of
Wu et al. (2016) on both WMT'14 English-German and WMT'14 English-French
translation at an order of magnitude faster speed, both on GPU and CPU.