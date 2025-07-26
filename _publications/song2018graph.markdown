---
layout: publication
title: A Graph-to-sequence Model For Amr-to-text Generation
authors: Linfeng Song, Yue Zhang, Zhiguo Wang, Daniel Gildea
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2018
bibkey: song2018graph
citations: 201
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.02473'}]
tags: ["Model Architecture"]
short_authors: Song et al.
---
The problem of AMR-to-text generation is to recover a text representing the
same meaning as an input AMR graph. The current state-of-the-art method uses a
sequence-to-sequence model, leveraging LSTM for encoding a linearized AMR
structure. Although being able to model non-local semantic information, a
sequence LSTM can lose information from the AMR graph structure, and thus faces
challenges with large graphs, which result in long sequences. We introduce a
neural graph-to-sequence model, using a novel LSTM structure for directly
encoding graph-level semantics. On a standard benchmark, our model shows
superior results to existing methods in the literature.