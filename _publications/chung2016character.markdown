---
layout: publication
title: A Character-level Decoder Without Explicit Segmentation For Neural Machine
  Translation
authors: Junyoung Chung, Kyunghyun Cho, Yoshua Bengio
conference: 'Proceedings of the 54th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2016
bibkey: chung2016character
citations: 238
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1603.06147'}]
tags: ["Model Architecture"]
short_authors: Junyoung Chung, Kyunghyun Cho, Yoshua Bengio
---
The existing machine translation systems, whether phrase-based or neural,
have relied almost exclusively on word-level modelling with explicit
segmentation. In this paper, we ask a fundamental question: can neural machine
translation generate a character sequence without any explicit segmentation? To
answer this question, we evaluate an attention-based encoder-decoder with a
subword-level encoder and a character-level decoder on four language
pairs--En-Cs, En-De, En-Ru and En-Fi-- using the parallel corpora from WMT'15.
Our experiments show that the models with a character-level decoder outperform
the ones with a subword-level decoder on all of the four language pairs.
Furthermore, the ensembles of neural models with a character-level decoder
outperform the state-of-the-art non-neural machine translation systems on
En-Cs, En-De and En-Fi and perform comparably on En-Ru.