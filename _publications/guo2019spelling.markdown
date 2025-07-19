---
layout: publication
title: A Spelling Correction Model For End-to-end Speech Recognition
authors: Guo Jinxi, Sainath Tara N., Weiss Ron J.
conference: ICASSP 2019 - 2019 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2019
bibkey: guo2019spelling
citations: 137
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.07178'}]
tags: [Training Techniques, Attention Mechanism, Tools, ICASSP, Model Architecture,
  Datasets]
---
Attention-based sequence-to-sequence models for speech recognition jointly
train an acoustic model, language model (LM), and alignment mechanism using a
single neural network and require only parallel audio-text pairs. Thus, the
language model component of the end-to-end model is only trained on transcribed
audio-text pairs, which leads to performance degradation especially on rare
words. While there have been a variety of work that look at incorporating an
external LM trained on text-only data into the end-to-end framework, none of
them have taken into account the characteristic error distribution made by the
model. In this paper, we propose a novel approach to utilizing text-only data,
by training a spelling correction (SC) model to explicitly correct those
errors. On the LibriSpeech dataset, we demonstrate that the proposed model
results in an 18.6% relative improvement in WER over the baseline model when
directly correcting top ASR hypothesis, and a 29.0% relative improvement when
further rescoring an expanded n-best list using an external LM.