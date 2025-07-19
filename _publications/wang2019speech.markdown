---
layout: publication
title: Speech Emotion Recognition With Dual-sequence LSTM Architecture
authors: Wang et al.
conference: ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2019
bibkey: wang2019speech
citations: 118
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.08874'}]
tags: [ICASSP, RAG, Model Architecture, Multimodal Models]
---
Speech Emotion Recognition (SER) has emerged as a critical component of the
next generation human-machine interfacing technologies. In this work, we
propose a new dual-level model that predicts emotions based on both MFCC
features and mel-spectrograms produced from raw audio signals. Each utterance
is preprocessed into MFCC features and two mel-spectrograms at different
time-frequency resolutions. A standard LSTM processes the MFCC features, while
a novel LSTM architecture, denoted as Dual-Sequence LSTM (DS-LSTM), processes
the two mel-spectrograms simultaneously. The outputs are later averaged to
produce a final classification of the utterance. Our proposed model achieves,
on average, a weighted accuracy of 72.7% and an unweighted accuracy of
73.3%---a 6% improvement over current state-of-the-art unimodal models---and is
comparable with multimodal models that leverage textual information as well as
audio signals.