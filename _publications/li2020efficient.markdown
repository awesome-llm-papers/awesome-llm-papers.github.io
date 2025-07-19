---
layout: publication
title: Efficient One-pass End-to-end Entity Linking For Questions
authors: Li et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: li2020efficient
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.02413'}]
tags: [EMNLP]
---
We present ELQ, a fast end-to-end entity linking model for questions, which
uses a biencoder to jointly perform mention detection and linking in one pass.
Evaluated on WebQSP and GraphQuestions with extended annotations that cover
multiple entities per question, ELQ outperforms the previous state of the art
by a large margin of +12.7% and +19.6% F1, respectively. With a very fast
inference time (1.57 examples/s on a single CPU), ELQ can be useful for
downstream question answering systems. In a proof-of-concept experiment, we
demonstrate that using ELQ significantly improves the downstream QA performance
of GraphRetriever (arXiv:1911.03868). Code and data available at
https://github.com/facebookresearch/BLINK/tree/master/elq