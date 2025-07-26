---
layout: publication
title: A Comparative Study On Transformer Vs RNN In Speech Applications
authors: Shigeki Karita, Nanxin Chen, Tomoki Hayashi, Takaaki Hori, Hirofumi Inaguma,
  Ziyan Jiang, Masao Someki, Nelson Enrique Yalta Soplin, Ryuichi Yamamoto, Xiaofei
  Wang, Shinji Watanabe, Takenori Yoshimura, Wangyou Zhang
conference: 2019 IEEE Automatic Speech Recognition and Understanding Workshop (ASRU)
year: 2019
bibkey: karita2019comparative
citations: 461
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.06317'}]
tags: ["ASRU", "Applications", "Model Architecture"]
short_authors: Karita et al.
---
Sequence-to-sequence models have been widely used in end-to-end speech
processing, for example, automatic speech recognition (ASR), speech translation
(ST), and text-to-speech (TTS). This paper focuses on an emergent
sequence-to-sequence model called Transformer, which achieves state-of-the-art
performance in neural machine translation and other natural language processing
applications. We undertook intensive studies in which we experimentally
compared and analyzed Transformer and conventional recurrent neural networks
(RNN) in a total of 15 ASR, one multilingual ASR, one ST, and two TTS
benchmarks. Our experiments revealed various training tips and significant
performance benefits obtained with Transformer for each task including the
surprising superiority of Transformer in 13/15 ASR benchmarks in comparison
with RNN. We are preparing to release Kaldi-style reproducible recipes using
open source and publicly available datasets for all the ASR, ST, and TTS tasks
for the community to succeed our exciting outcomes.