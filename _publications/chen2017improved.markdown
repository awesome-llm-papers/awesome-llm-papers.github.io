---
layout: publication
title: Improved Neural Machine Translation With A Syntax-aware Encoder And Decoder
authors: Huadong Chen, Shujian Huang, David Chiang, Jiajun Chen
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: chen2017improved
citations: 130
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.05436'}]
tags: ["Tools"]
short_authors: Chen et al.
---
Most neural machine translation (NMT) models are based on the sequential
encoder-decoder framework, which makes no use of syntactic information. In this
paper, we improve this model by explicitly incorporating source-side syntactic
trees. More specifically, we propose (1) a bidirectional tree encoder which
learns both sequential and tree structured representations; (2) a tree-coverage
model that lets the attention depend on the source-side syntax. Experiments on
Chinese-English translation demonstrate that our proposed models outperform the
sequential attentional model as well as a stronger baseline with a bottom-up
tree encoder and word coverage.