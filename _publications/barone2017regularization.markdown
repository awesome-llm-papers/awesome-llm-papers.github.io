---
layout: publication
title: Regularization Techniques For Fine-tuning In Neural Machine Translation
authors: Barone et al.
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: barone2017regularization
citations: 96
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.09920'}]
tags: [Training Techniques, Fine Tuning, EMNLP, Datasets, SLT]
---
We investigate techniques for supervised domain adaptation for neural machine
translation where an existing model trained on a large out-of-domain dataset is
adapted to a small in-domain dataset. In this scenario, overfitting is a major
challenge. We investigate a number of techniques to reduce overfitting and
improve transfer learning, including regularization techniques such as dropout
and L2-regularization towards an out-of-domain prior. In addition, we introduce
tuneout, a novel regularization technique inspired by dropout. We apply these
techniques, alone and in combination, to neural machine translation, obtaining
improvements on IWSLT datasets for English->German and English->Russian. We
also investigate the amounts of in-domain training data needed for domain
adaptation in NMT, and find a logarithmic relationship between the amount of
training data and gain in BLEU score.