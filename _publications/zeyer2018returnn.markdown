---
layout: publication
title: RETURNN As A Generic Flexible Neural Toolkit With Application To Translation
  And Speech Recognition
authors: Zeyer Albert, Alkhouli Tamer, Ney Hermann
conference: Proceedings of ACL 2018, System Demonstrations
year: 2018
bibkey: zeyer2018returnn
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.05225'}]
tags: [Model Architecture, Training Techniques, ACL, Applications, Attention Mechanism,
  Alt]
---
We compare the fast training and decoding speed of RETURNN of attention
models for translation, due to fast CUDA LSTM kernels, and a fast pure
TensorFlow beam search decoder. We show that a layer-wise pretraining scheme
for recurrent attention models gives over 1% BLEU improvement absolute and it
allows to train deeper recurrent encoder networks. Promising preliminary
results on max. expected BLEU training are presented. We are able to train
state-of-the-art models for translation and end-to-end models for speech
recognition and show results on WMT 2017 and Switchboard. The flexibility of
RETURNN allows a fast research feedback loop to experiment with alternative
architectures, and its generality allows to use it on a wide range of
applications.