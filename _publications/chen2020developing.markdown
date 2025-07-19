---
layout: publication
title: Developing Real-time Streaming Transformer Transducer For Speech Recognition
  On Large-scale Dataset
authors: Chen et al.
conference: ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2020
bibkey: chen2020developing
citations: 148
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.11395'}]
tags: [Attention Mechanism, Transformer, ICASSP, Model Architecture, Applications,
  Datasets]
---
Recently, Transformer based end-to-end models have achieved great success in
many areas including speech recognition. However, compared to LSTM models, the
heavy computational cost of the Transformer during inference is a key issue to
prevent their applications. In this work, we explored the potential of
Transformer Transducer (T-T) models for the fist pass decoding with low latency
and fast speed on a large-scale dataset. We combine the idea of Transformer-XL
and chunk-wise streaming processing to design a streamable Transformer
Transducer model. We demonstrate that T-T outperforms the hybrid model, RNN
Transducer (RNN-T), and streamable Transformer attention-based encoder-decoder
model in the streaming scenario. Furthermore, the runtime cost and latency can
be optimized with a relatively small look-ahead.