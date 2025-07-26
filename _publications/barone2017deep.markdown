---
layout: publication
title: Deep Architectures For Neural Machine Translation
authors: "Antonio Valerio Miceli Barone, Jind\u0159ich Helcl, Rico Sennrich, Barry\
  \ Haddow, Alexandra Birch"
conference: Proceedings of the Second Conference on Machine Translation
year: 2017
bibkey: barone2017deep
citations: 107
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.07631'}]
tags: ["Model Architecture"]
short_authors: Barone et al.
---
It has been shown that increasing model depth improves the quality of neural
machine translation. However, different architectural variants to increase
model depth have been proposed, and so far, there has been no thorough
comparative study.
  In this work, we describe and evaluate several existing approaches to
introduce depth in neural machine translation. Additionally, we explore novel
architectural variants, including deep transition RNNs, and we vary how
attention is used in the deep decoder. We introduce a novel "BiDeep" RNN
architecture that combines deep transition RNNs and stacked RNNs.
  Our evaluation is carried out on the English to German WMT news translation
dataset, using a single-GPU machine for both training and inference. We find
that several of our proposed architectures improve upon existing approaches in
terms of speed and translation quality. We obtain best improvements with a
BiDeep RNN of combined depth 8, obtaining an average improvement of 1.5 BLEU
over a strong shallow baseline.
  We release our code for ease of adoption.