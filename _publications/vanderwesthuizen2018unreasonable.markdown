---
layout: publication
title: The Unreasonable Effectiveness Of The Forget Gate
authors: Jos van Der Westhuizen, Joan Lasenby
conference: Arxiv
year: 2018
bibkey: vanderwesthuizen2018unreasonable
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.04849'}]
tags: ["Model Architecture"]
short_authors: Jos van Der Westhuizen, Joan Lasenby
---
Given the success of the gated recurrent unit, a natural question is whether
all the gates of the long short-term memory (LSTM) network are necessary.
Previous research has shown that the forget gate is one of the most important
gates in the LSTM. Here we show that a forget-gate-only version of the LSTM
with chrono-initialized biases, not only provides computational savings but
outperforms the standard LSTM on multiple benchmark datasets and competes with
some of the best contemporary models. Our proposed network, the JANET, achieves
accuracies of 99% and 92.5% on the MNIST and pMNIST datasets, outperforming the
standard LSTM which yields accuracies of 98.5% and 91%.