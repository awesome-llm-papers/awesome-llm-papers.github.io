---
layout: publication
title: Efficient Bidirectional Neural Machine Translation
authors: Tan et al.
conference: Transactions of the Association for Computational Linguistics
year: 2019
bibkey: tan2019efficient
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.09329'}]
tags: [TACL, ACL, Training Techniques]
---
The encoder-decoder based neural machine translation usually generates a
target sequence token by token from left to right. Due to error propagation,
the tokens in the right side of the generated sequence are usually of poorer
quality than those in the left side. In this paper, we propose an efficient
method to generate a sequence in both left-to-right and right-to-left manners
using a single encoder and decoder, combining the advantages of both generation
directions. Experiments on three translation tasks show that our method
achieves significant improvements over conventional unidirectional approach.
Compared with ensemble methods that train and combine two models with different
generation directions, our method saves 50% model parameters and about 40%
training time, and also improve inference speed.