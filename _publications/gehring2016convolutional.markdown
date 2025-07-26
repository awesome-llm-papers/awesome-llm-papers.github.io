---
layout: publication
title: A Convolutional Encoder Model For Neural Machine Translation
authors: Jonas Gehring, Michael Auli, David Grangier, Yann N. Dauphin
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: gehring2016convolutional
citations: 434
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.02344'}]
tags: ["Model Architecture"]
short_authors: Gehring et al.
---
The prevalent approach to neural machine translation relies on bi-directional
LSTMs to encode the source sentence. In this paper we present a faster and
simpler architecture based on a succession of convolutional layers. This allows
to encode the entire source sentence simultaneously compared to recurrent
networks for which computation is constrained by temporal dependencies. On
WMT'16 English-Romanian translation we achieve competitive accuracy to the
state-of-the-art and we outperform several recently published results on the
WMT'15 English-German task. Our models obtain almost the same accuracy as a
very deep LSTM setup on WMT'14 English-French translation. Our convolutional
encoder speeds up CPU decoding by more than two times at the same or higher
accuracy as a strong bi-directional LSTM baseline.