---
layout: publication
title: Glancing Transformer For Non-autoregressive Neural Machine Translation
authors: Lihua Qian, Hao Zhou, Yu Bao, Mingxuan Wang, Lin Qiu, Weinan Zhang, Yong
  Yu, Lei Li
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: qian2020glancing
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2008.07905'}]
tags: ["Model Architecture"]
short_authors: Qian et al.
---
Recent work on non-autoregressive neural machine translation (NAT) aims at
improving the efficiency by parallel decoding without sacrificing the quality.
However, existing NAT methods are either inferior to Transformer or require
multiple decoding passes, leading to reduced speedup. We propose the Glancing
Language Model (GLM), a method to learn word interdependency for single-pass
parallel generation models. With GLM, we develop Glancing Transformer (GLAT)
for machine translation. With only single-pass parallel decoding, GLAT is able
to generate high-quality translation with 8-15 times speedup. Experiments on
multiple WMT language directions show that GLAT outperforms all previous single
pass non-autoregressive methods, and is nearly comparable to Transformer,
reducing the gap to 0.25-0.9 BLEU points.