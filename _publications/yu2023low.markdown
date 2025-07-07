---
layout: publication
title: Low-rank Adaptation Of Large Language Model Rescoring For Parameter-efficient
  Speech Recognition
authors: Yu Yu et al.
conference: Proc. IEEE ASRU Workshop Dec. 2023
year: 2023
citations: 20
bibkey: yu2023low
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.15223'}]
tags: [Training Techniques, INTERSPEECH, Fine-Tuning, BERT, Language Modeling, Model
    Architecture]
---
We propose a neural language modeling system based on low-rank adaptation
(LoRA) for speech recognition output rescoring. Although pretrained language
models (LMs) like BERT have shown superior performance in second-pass
rescoring, the high computational cost of scaling up the pretraining stage and
adapting the pretrained models to specific domains limit their practical use in
rescoring. Here we present a method based on low-rank decomposition to train a
rescoring BERT model and adapt it to new domains using only a fraction (0.08%)
of the pretrained parameters. These inserted matrices are optimized through a
discriminative training objective along with a correlation-based regularization
loss. The proposed low-rank adaptation Rescore-BERT (LoRB) architecture is
evaluated on LibriSpeech and internal datasets with decreased training times by
factors between 5.4 and 3.6.