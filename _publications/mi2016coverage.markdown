---
layout: publication
title: Coverage Embedding Models For Neural Machine Translation
authors: Haitao Mi, Baskaran Sankaran, Zhiguo Wang, Abe Ittycheriah
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: mi2016coverage
citations: 137
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1605.03148'}]
tags: ["EMNLP"]
short_authors: Mi et al.
---
In this paper, we enhance the attention-based neural machine translation
(NMT) by adding explicit coverage embedding models to alleviate issues of
repeating and dropping translations in NMT. For each source word, our model
starts with a full coverage embedding vector to track the coverage status, and
then keeps updating it with neural networks as the translation goes.
Experiments on the large-scale Chinese-to-English task show that our enhanced
model improves the translation quality significantly on various test sets over
the strong large vocabulary NMT system.