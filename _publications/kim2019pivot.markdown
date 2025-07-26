---
layout: publication
title: Pivot-based Transfer Learning For Neural Machine Translation Between Non-english
  Languages
authors: Yunsu Kim, Petre Petrov, Pavel Petrushkov, Shahram Khadivi, Hermann Ney
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: kim2019pivot
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.09524'}]
tags: ["EMNLP", "Fine-Tuning", "Training Techniques"]
short_authors: Kim et al.
---
We present effective pre-training strategies for neural machine translation
(NMT) using parallel corpora involving a pivot language, i.e., source-pivot and
pivot-target, leading to a significant improvement in source-target
translation. We propose three methods to increase the relation among source,
pivot, and target languages in the pre-training: 1) step-wise training of a
single model for different language pairs, 2) additional adapter component to
smoothly connect pre-trained encoder and decoder, and 3) cross-lingual encoder
training via autoencoding of the pivot language. Our methods greatly outperform
multilingual models up to +2.6% BLEU in WMT 2019 French-German and German-Czech
tasks. We show that our improvements are valid also in zero-shot/zero-resource
scenarios.