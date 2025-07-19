---
layout: publication
title: 'Google USM: Scaling Automatic Speech Recognition Beyond 100 Languages'
authors: Zhang et al.
conference: Arxiv
year: 2023
bibkey: zhang2023google
citations: 96
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.01037'}]
tags: [Training Techniques, Efficiency And Optimization, Fine Tuning, Quantization,
  Datasets]
---
We introduce the Universal Speech Model (USM), a single large model that
performs automatic speech recognition (ASR) across 100+ languages. This is
achieved by pre-training the encoder of the model on a large unlabeled
multilingual dataset of 12 million (M) hours spanning over 300 languages, and
fine-tuning on a smaller labeled dataset. We use multilingual pre-training with
random-projection quantization and speech-text modality matching to achieve
state-of-the-art performance on downstream multilingual ASR and speech-to-text
translation tasks. We also demonstrate that despite using a labeled training
set 1/7-th the size of that used for the Whisper model, our model exhibits
comparable or better performance on both in-domain and out-of-domain speech
recognition tasks across many languages.