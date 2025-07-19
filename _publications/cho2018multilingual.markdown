---
layout: publication
title: 'Multilingual Sequence-to-sequence Speech Recognition: Architecture, Transfer
  Learning, And Language Modeling'
authors: Cho et al.
conference: 2018 IEEE Spoken Language Technology Workshop (SLT)
year: 2018
bibkey: cho2018multilingual
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.03459'}]
tags: [Training Techniques, Model Architecture, Language Modeling, Fine Tuning, SLT]
---
Sequence-to-sequence (seq2seq) approach for low-resource ASR is a relatively
new direction in speech research. The approach benefits by performing model
training without using lexicon and alignments. However, this poses a new
problem of requiring more data compared to conventional DNN-HMM systems. In
this work, we attempt to use data from 10 BABEL languages to build a
multi-lingual seq2seq model as a prior model, and then port them towards 4
other BABEL languages using transfer learning approach. We also explore
different architectures for improving the prior multilingual seq2seq model. The
paper also discusses the effect of integrating a recurrent neural network
language model (RNNLM) with a seq2seq model during decoding. Experimental
results show that the transfer learning approach from the multilingual model
shows substantial gains over monolingual models across all 4 BABEL languages.
Incorporating an RNNLM also brings significant improvements in terms of %WER,
and achieves recognition performance comparable to the models trained with
twice more training data.