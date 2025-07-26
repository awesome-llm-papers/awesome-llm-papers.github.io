---
layout: publication
title: AMR Parsing Via Graph-sequence Iterative Inference
authors: Deng Cai, Wai Lam
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: cai2020amr
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.05572'}]
tags: ["Model Architecture"]
short_authors: Deng Cai, Wai Lam
---
We propose a new end-to-end model that treats AMR parsing as a series of dual
decisions on the input sequence and the incrementally constructed graph. At
each time step, our model performs multiple rounds of attention, reasoning, and
composition that aim to answer two critical questions: (1) which part of the
input \textit\{sequence\} to abstract; and (2) where in the output \textit\{graph\}
to construct the new concept. We show that the answers to these two questions
are mutually causalities. We design a model based on iterative inference that
helps achieve better answers in both perspectives, leading to greatly improved
parsing accuracy. Our experimental results significantly outperform all
previously reported \textsc\{Smatch\} scores by large margins. Remarkably,
without the help of any large-scale pre-trained language model (e.g., BERT),
our model already surpasses previous state-of-the-art using BERT. With the help
of BERT, we can push the state-of-the-art results to 80.2% on LDC2017T10 (AMR
2.0) and 75.4% on LDC2014T12 (AMR 1.0).