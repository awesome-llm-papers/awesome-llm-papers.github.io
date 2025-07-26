---
layout: publication
title: Self-attention With Relative Position Representations
authors: Peter Shaw, Jakob Uszkoreit, Ashish Vaswani
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 2
  (Short Papers)'
year: 2018
bibkey: shaw2018self
citations: 1977
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1803.02155'}]
tags: ["Model Architecture"]
short_authors: Peter Shaw, Jakob Uszkoreit, Ashish Vaswani
---
Relying entirely on an attention mechanism, the Transformer introduced by
Vaswani et al. (2017) achieves state-of-the-art results for machine
translation. In contrast to recurrent and convolutional neural networks, it
does not explicitly model relative or absolute position information in its
structure. Instead, it requires adding representations of absolute positions to
its inputs. In this work we present an alternative approach, extending the
self-attention mechanism to efficiently consider representations of the
relative positions, or distances between sequence elements. On the WMT 2014
English-to-German and English-to-French translation tasks, this approach yields
improvements of 1.3 BLEU and 0.3 BLEU over absolute position representations,
respectively. Notably, we observe that combining relative and absolute position
representations yields no further improvement in translation quality. We
describe an efficient implementation of our method and cast it as an instance
of relation-aware self-attention mechanisms that can generalize to arbitrary
graph-labeled inputs.