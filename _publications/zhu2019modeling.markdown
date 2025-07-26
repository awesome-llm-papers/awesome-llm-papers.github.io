---
layout: publication
title: Modeling Graph Structure In Transformer For Better Amr-to-text Generation
authors: Jie Zhu, Junhui Li, Muhua Zhu, Longhua Qian, Min Zhang, Guodong Zhou
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: zhu2019modeling
citations: 97
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.00136'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Zhu et al.
---
Recent studies on AMR-to-text generation often formalize the task as a
sequence-to-sequence (seq2seq) learning problem by converting an Abstract
Meaning Representation (AMR) graph into a word sequence. Graph structures are
further modeled into the seq2seq framework in order to utilize the structural
information in the AMR graphs. However, previous approaches only consider the
relations between directly connected concepts while ignoring the rich structure
in AMR graphs. In this paper we eliminate such a strong limitation and propose
a novel structure-aware self-attention approach to better modeling the
relations between indirectly connected concepts in the state-of-the-art seq2seq
model, i.e., the Transformer. In particular, a few different methods are
explored to learn structural representations between two concepts. Experimental
results on English AMR benchmark datasets show that our approach significantly
outperforms the state of the art with 29.66 and 31.82 BLEU scores on LDC2015E86
and LDC2017T10, respectively. To the best of our knowledge, these are the best
results achieved so far by supervised models on the benchmarks.