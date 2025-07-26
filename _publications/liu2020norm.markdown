---
layout: publication
title: Norm-based Curriculum Learning For Neural Machine Translation
authors: Xuebo Liu, Houtim Lai, Derek F. Wong, Lidia S. Chao
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: liu2020norm
citations: 99
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.02014'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Liu et al.
---
A neural machine translation (NMT) system is expensive to train, especially
with high-resource settings. As the NMT architectures become deeper and wider,
this issue gets worse and worse. In this paper, we aim to improve the
efficiency of training an NMT by introducing a novel norm-based curriculum
learning method. We use the norm (aka length or module) of a word embedding as
a measure of 1) the difficulty of the sentence, 2) the competence of the model,
and 3) the weight of the sentence. The norm-based sentence difficulty takes the
advantages of both linguistically motivated and model-based sentence
difficulties. It is easy to determine and contains learning-dependent features.
The norm-based model competence makes NMT learn the curriculum in a fully
automated way, while the norm-based sentence weight further enhances the
learning of the vector representation of the NMT. Experimental results for the
WMT'14 English-German and WMT'17 Chinese-English translation tasks demonstrate
that the proposed method outperforms strong baselines in terms of BLEU score
(+1.17/+1.56) and training speedup (2.22x/3.33x).