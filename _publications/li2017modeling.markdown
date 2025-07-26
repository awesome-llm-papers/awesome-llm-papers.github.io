---
layout: publication
title: Modeling Source Syntax For Neural Machine Translation
authors: Junhui Li, Deyi Xiong, Zhaopeng Tu, Muhua Zhu, Min Zhang, Guodong Zhou
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: li2017modeling
citations: 133
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1705.01020'}]
tags: ["COLING", "EACL", "EMNLP", "LREC", "Model Architecture", "NAACL", "TACL"]
short_authors: Li et al.
---
Even though a linguistics-free sequence to sequence model in neural machine
translation (NMT) has certain capability of implicitly learning syntactic
information of source sentences, this paper shows that source syntax can be
explicitly incorporated into NMT effectively to provide further improvements.
Specifically, we linearize parse trees of source sentences to obtain structural
label sequences. On the basis, we propose three different sorts of encoders to
incorporate source syntax into NMT: 1) Parallel RNN encoder that learns word
and label annotation vectors parallelly; 2) Hierarchical RNN encoder that
learns word and label annotation vectors in a two-level hierarchy; and 3) Mixed
RNN encoder that stitchingly learns word and label annotation vectors over
sequences where words and labels are mixed. Experimentation on
Chinese-to-English translation demonstrates that all the three proposed
syntactic encoders are able to improve translation accuracy. It is interesting
to note that the simplest RNN encoder, i.e., Mixed RNN encoder yields the best
performance with an significant improvement of 1.4 BLEU points. Moreover, an
in-depth analysis from several perspectives is provided to reveal how source
syntax benefits NMT.