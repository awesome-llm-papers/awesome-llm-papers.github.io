---
layout: publication
title: 'Wronging A Right: Generating Better Errors To Improve Grammatical Error Detection'
authors: Kasewa Sudhanshu, Stenetorp Pontus, Riedel Sebastian
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: kasewa2018wronging
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.00668'}]
tags: [Datasets, Model Architecture, Training Techniques, EMNLP]
---
Grammatical error correction, like other machine learning tasks, greatly
benefits from large quantities of high quality training data, which is
typically expensive to produce. While writing a program to automatically
generate realistic grammatical errors would be difficult, one could learn the
distribution of naturallyoccurring errors and attempt to introduce them into
other datasets. Initial work on inducing errors in this way using statistical
machine translation has shown promise; we investigate cheaply constructing
synthetic samples, given a small corpus of human-annotated data, using an
off-the-rack attentive sequence-to-sequence model and a straight-forward
post-processing procedure. Our approach yields error-filled artificial data
that helps a vanilla bi-directional LSTM to outperform the previous state of
the art at grammatical error detection, and a previously introduced model to
gain further improvements of over 5% \\(F_\{0.5\}\\) score. When attempting to
determine if a given sentence is synthetic, a human annotator at best achieves
39.39 \\(F_1\\) score, indicating that our model generates mostly human-like
instances.