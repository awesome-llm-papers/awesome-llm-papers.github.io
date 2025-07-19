---
layout: publication
title: A Streaming On-device End-to-end Model Surpassing Server-side Conventional
  Model Quality And Latency
authors: Sainath et al.
conference: ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2020
bibkey: sainath2020streaming
citations: 203
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.12710'}]
tags: [ICASSP, Efficiency And Optimization, Training Techniques]
---
Thus far, end-to-end (E2E) models have not been shown to outperform
state-of-the-art conventional models with respect to both quality, i.e., word
error rate (WER), and latency, i.e., the time the hypothesis is finalized after
the user stops speaking. In this paper, we develop a first-pass Recurrent
Neural Network Transducer (RNN-T) model and a second-pass Listen, Attend, Spell
(LAS) rescorer that surpasses a conventional model in both quality and latency.
On the quality side, we incorporate a large number of utterances across varied
domains to increase acoustic diversity and the vocabulary seen by the model. We
also train with accented English speech to make the model more robust to
different pronunciations. In addition, given the increased amount of training
data, we explore a varied learning rate schedule. On the latency front, we
explore using the end-of-sentence decision emitted by the RNN-T model to close
the microphone, and also introduce various optimizations to improve the speed
of LAS rescoring. Overall, we find that RNN-T+LAS offers a better WER and
latency tradeoff compared to a conventional model. For example, for the same
latency, RNN-T+LAS obtains a 8% relative improvement in WER, while being more
than 400-times smaller in model size.