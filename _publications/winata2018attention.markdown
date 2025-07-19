---
layout: publication
title: Attention-based LSTM For Psychological Stress Detection From Spoken Language
  Using Distant Supervision
authors: Winata Genta Indra, Kampman Onno Pepijn, Fung Pascale
conference: 2018 IEEE International Conference on Acoustics, Speech and Signal Processing
  (ICASSP)
year: 2018
bibkey: winata2018attention
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.12307'}]
tags: [Training Techniques, Attention Mechanism, Transformer, ICASSP, Model Architecture,
  Security, Fine Tuning, Datasets]
---
We propose a Long Short-Term Memory (LSTM) with attention mechanism to
classify psychological stress from self-conducted interview transcriptions. We
apply distant supervision by automatically labeling tweets based on their
hashtag content, which complements and expands the size of our corpus. This
additional data is used to initialize the model parameters, and which it is
fine-tuned using the interview data. This improves the model's robustness,
especially by expanding the vocabulary size. The bidirectional LSTM model with
attention is found to be the best model in terms of accuracy (74.1%) and
f-score (74.3%). Furthermore, we show that distant supervision fine-tuning
enhances the model's performance by 1.6% accuracy and 2.1% f-score. The
attention mechanism helps the model to select informative words.