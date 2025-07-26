---
layout: publication
title: Unsupervised Pretraining For Sequence To Sequence Learning
authors: Prajit Ramachandran, Peter J. Liu, Quoc V. Le
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: ramachandran2016unsupervised
citations: 275
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.02683'}]
tags: ["EMNLP"]
short_authors: Prajit Ramachandran, Peter J. Liu, Quoc V. Le
---
This work presents a general unsupervised learning method to improve the
accuracy of sequence to sequence (seq2seq) models. In our method, the weights
of the encoder and decoder of a seq2seq model are initialized with the
pretrained weights of two language models and then fine-tuned with labeled
data. We apply this method to challenging benchmarks in machine translation and
abstractive summarization and find that it significantly improves the
subsequent supervised models. Our main result is that pretraining improves the
generalization of seq2seq models. We achieve state-of-the art results on the
WMT English\\(\rightarrow\\)German task, surpassing a range of methods using both
phrase-based machine translation and neural machine translation. Our method
achieves a significant improvement of 1.3 BLEU from the previous best models on
both WMT'14 and WMT'15 English\\(\rightarrow\\)German. We also conduct human
evaluations on abstractive summarization and find that our method outperforms a
purely supervised learning baseline in a statistically significant manner.