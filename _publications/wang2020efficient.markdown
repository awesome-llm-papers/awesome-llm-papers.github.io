---
layout: publication
title: Efficient End-to-end Speech Recognition Using Performers In Conformers
authors: Wang Peidong, Wang Deliang
conference: ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2020
bibkey: wang2020efficient
citations: 140
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2011.04196'}]
tags: [Attention Mechanism, Transformer, ICASSP, Efficiency And Optimization, Model
    Architecture, Datasets]
---
On-device end-to-end speech recognition poses a high requirement on model
efficiency. Most prior works improve the efficiency by reducing model sizes. We
propose to reduce the complexity of model architectures in addition to model
sizes. More specifically, we reduce the floating-point operations in conformer
by replacing the transformer module with a performer. The proposed
attention-based efficient end-to-end speech recognition model yields
competitive performance on the LibriSpeech corpus with 10 millions of
parameters and linear computation complexity. The proposed model also
outperforms previous lightweight end-to-end models by about 20% relatively in
word error rate.