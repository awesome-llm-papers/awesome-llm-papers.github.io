---
layout: publication
title: Efficiently Trainable Text-to-speech System Based On Deep Convolutional Networks
  With Guided Attention
authors: Hideyuki Tachibana, Katsuya Uenoyama, Shunsuke Aihara
conference: 2018 IEEE International Conference on Acoustics, Speech and Signal Processing
  (ICASSP)
year: 2018
bibkey: tachibana2017efficiently
citations: 273
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1710.08969'}]
tags: ["ICASSP", "Model Architecture", "Training Techniques"]
short_authors: Hideyuki Tachibana, Katsuya Uenoyama, Shunsuke Aihara
---
This paper describes a novel text-to-speech (TTS) technique based on deep
convolutional neural networks (CNN), without use of any recurrent units.
Recurrent neural networks (RNN) have become a standard technique to model
sequential data recently, and this technique has been used in some cutting-edge
neural TTS techniques. However, training RNN components often requires a very
powerful computer, or a very long time, typically several days or weeks. Recent
other studies, on the other hand, have shown that CNN-based sequence synthesis
can be much faster than RNN-based techniques, because of high
parallelizability. The objective of this paper is to show that an alternative
neural TTS based only on CNN alleviate these economic costs of training. In our
experiment, the proposed Deep Convolutional TTS was sufficiently trained
overnight (15 hours), using an ordinary gaming PC equipped with two GPUs, while
the quality of the synthesized speech was almost acceptable.