---
layout: publication
title: Exploring Neural Transducers For End-to-end Speech Recognition
authors: Battenberg et al.
conference: 2017 IEEE Automatic Speech Recognition and Understanding Workshop (ASRU)
year: 2017
bibkey: battenberg2017exploring
citations: 245
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.07413'}]
tags: [Attention Mechanism, ASRU, Evaluation, Model Architecture, Datasets]
---
In this work, we perform an empirical comparison among the CTC,
RNN-Transducer, and attention-based Seq2Seq models for end-to-end speech
recognition. We show that, without any language model, Seq2Seq and
RNN-Transducer models both outperform the best reported CTC models with a
language model, on the popular Hub5'00 benchmark. On our internal diverse
dataset, these trends continue - RNNTransducer models rescored with a language
model after beam search outperform our best CTC models. These results simplify
the speech recognition pipeline so that decoding can now be expressed purely as
neural network operations. We also study how the choice of encoder architecture
affects the performance of the three models - when all encoder layers are
forward only, and when encoders downsample the input representation
aggressively.