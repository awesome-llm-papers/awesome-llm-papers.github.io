---
layout: publication
title: Analyzing ASR Pretraining For Low-resource Speech-to-text Translation
authors: Mihaela C. Stoian, Sameer Bansal, Sharon Goldwater
conference: ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2020
bibkey: stoian2019analyzing
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.10762'}]
tags: ["Datasets", "ICASSP"]
short_authors: Mihaela C. Stoian, Sameer Bansal, Sharon Goldwater
---
Previous work has shown that for low-resource source languages, automatic
speech-to-text translation (AST) can be improved by pretraining an end-to-end
model on automatic speech recognition (ASR) data from a high-resource language.
However, it is not clear what factors --e.g., language relatedness or size of
the pretraining data-- yield the biggest improvements, or whether pretraining
can be effectively combined with other methods such as data augmentation. Here,
we experiment with pretraining on datasets of varying sizes, including
languages related and unrelated to the AST source language. We find that the
best predictor of final AST performance is the word error rate of the
pretrained ASR model, and that differences in ASR/AST performance correlate
with how phonetic information is encoded in the later RNN layers of our model.
We also show that pretraining and data augmentation yield complementary
benefits for AST.