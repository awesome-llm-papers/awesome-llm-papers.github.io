---
layout: publication
title: Robust Neural Machine Translation With Doubly Adversarial Inputs
authors: Yong Cheng, Lu Jiang, Wolfgang Macherey
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: cheng2019robust
citations: 233
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.02443'}]
tags: ["Model Architecture"]
short_authors: Yong Cheng, Lu Jiang, Wolfgang Macherey
---
Neural machine translation (NMT) often suffers from the vulnerability to
noisy perturbations in the input. We propose an approach to improving the
robustness of NMT models, which consists of two parts: (1) attack the
translation model with adversarial source examples; (2) defend the translation
model with adversarial target inputs to improve its robustness against the
adversarial source inputs.For the generation of adversarial inputs, we propose
a gradient-based method to craft adversarial examples informed by the
translation loss over the clean inputs.Experimental results on Chinese-English
and English-German translation tasks demonstrate that our approach achieves
significant improvements (\\(2.8\\) and \\(1.6\\) BLEU points) over Transformer on
standard clean benchmarks as well as exhibiting higher robustness on noisy
data.