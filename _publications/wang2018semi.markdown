---
layout: publication
title: Semi-autoregressive Neural Machine Translation
authors: Chunqi Wang, Ji Zhang, Haiqing Chen
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: wang2018semi
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.08583'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Chunqi Wang, Ji Zhang, Haiqing Chen
---
Existing approaches to neural machine translation are typically
autoregressive models. While these models attain state-of-the-art translation
quality, they are suffering from low parallelizability and thus slow at
decoding long sequences. In this paper, we propose a novel model for fast
sequence generation --- the semi-autoregressive Transformer (SAT). The SAT
keeps the autoregressive property in global but relieves in local and thus is
able to produce multiple successive words in parallel at each time step.
Experiments conducted on English-German and Chinese-English translation tasks
show that the SAT achieves a good balance between translation quality and
decoding speed. On WMT'14 English-German translation, the SAT achieves
5.58\\(\times\\) speedup while maintains 88% translation quality, significantly
better than the previous non-autoregressive methods. When produces two words at
each time step, the SAT is almost lossless (only 1% degeneration in BLEU
score).