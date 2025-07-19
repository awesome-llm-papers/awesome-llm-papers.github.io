---
layout: publication
title: A Comparison Of Techniques For Language Model Integration In Encoder-decoder
  Speech Recognition
authors: Toshniwal et al.
conference: 2018 IEEE Spoken Language Technology Workshop (SLT)
year: 2018
bibkey: toshniwal2018comparison
citations: 158
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1807.10857'}]
tags: [Datasets, Training Techniques, Attention Mechanism, Evaluation, Model Architecture,
  SLT, Merging]
---
Attention-based recurrent neural encoder-decoder models present an elegant
solution to the automatic speech recognition problem. This approach folds the
acoustic model, pronunciation model, and language model into a single network
and requires only a parallel corpus of speech and text for training. However,
unlike in conventional approaches that combine separate acoustic and language
models, it is not clear how to use additional (unpaired) text. While there has
been previous work on methods addressing this problem, a thorough comparison
among methods is still lacking. In this paper, we compare a suite of past
methods and some of our own proposed methods for using unpaired text data to
improve encoder-decoder models. For evaluation, we use the medium-sized
Switchboard data set and the large-scale Google voice search and dictation data
sets. Our results confirm the benefits of using unpaired text across a range of
methods and data sets. Surprisingly, for first-pass decoding, the rather simple
approach of shallow fusion performs best across data sets. However, for Google
data sets we find that cold fusion has a lower oracle error rate and
outperforms other approaches after second-pass rescoring on the Google voice
search data set.