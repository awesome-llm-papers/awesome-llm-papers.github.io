---
layout: publication
title: 'Binarybert: Pushing The Limit Of BERT Quantization'
authors: Haoli Bai, Wei Zhang, Lu Hou, Lifeng Shang, Jing Jin, Xin Jiang, Qun Liu,
  Michael Lyu, Irwin King
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: bai2020binarybert
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.15701'}]
tags: ["Model Architecture"]
short_authors: Bai et al.
---
The rapid development of large pre-trained language models has greatly
increased the demand for model compression techniques, among which quantization
is a popular solution. In this paper, we propose BinaryBERT, which pushes BERT
quantization to the limit by weight binarization. We find that a binary BERT is
hard to be trained directly than a ternary counterpart due to its complex and
irregular loss landscape. Therefore, we propose ternary weight splitting, which
initializes BinaryBERT by equivalently splitting from a half-sized ternary
network. The binary model thus inherits the good performance of the ternary
one, and can be further enhanced by fine-tuning the new architecture after
splitting. Empirical results show that our BinaryBERT has only a slight
performance drop compared with the full-precision model while being 24x
smaller, achieving the state-of-the-art compression results on the GLUE and
SQuAD benchmarks.