---
layout: publication
title: Internal Language Model Adaptation With Text-only Data For End-to-end Speech
  Recognition
authors: Zhong Meng, Yashesh Gaur, Naoyuki Kanda, Jinyu Li, Xie Chen, Yu Wu, Yifan
  Gong
conference: 2021 IEEE Spoken Language Technology Workshop (SLT)
year: 2021
bibkey: meng2021internal
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.05354'}]
tags: ["SLT"]
short_authors: Meng et al.
---
Text-only adaptation of an end-to-end (E2E) model remains a challenging task
for automatic speech recognition (ASR). Language model (LM) fusion-based
approaches require an additional external LM during inference, significantly
increasing the computation cost. To overcome this, we propose an internal LM
adaptation (ILMA) of the E2E model using text-only data. Trained with
audio-transcript pairs, an E2E model implicitly learns an internal LM that
characterizes the token sequence probability which is approximated by the E2E
model output after zeroing out the encoder contribution. During ILMA, we
fine-tune the internal LM, i.e., the E2E components excluding the encoder, to
minimize a cross-entropy loss. To make ILMA effective, it is essential to train
the E2E model with an internal LM loss besides the standard E2E loss.
Furthermore, we propose to regularize ILMA by minimizing the Kullback-Leibler
divergence between the output distributions of the adapted and unadapted
internal LMs. ILMA is the most effective when we update only the last linear
layer of the joint network. ILMA enables a fast text-only adaptation of the E2E
model without increasing the run-time computational cost. Experimented with
30K-hour trained transformer transducer models, ILMA achieves up to 34.9%
relative word error rate reduction from the unadapted baseline.