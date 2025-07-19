---
layout: publication
title: Towards Language-universal End-to-end Speech Recognition
authors: Kim Suyoun, Seltzer Michael L.
conference: 2018 IEEE International Conference on Acoustics, Speech and Signal Processing
  (ICASSP)
year: 2017
bibkey: kim2017towards
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.02207'}]
tags: [ICASSP, Training Techniques]
---
Building speech recognizers in multiple languages typically involves
replicating a monolingual training recipe for each language, or utilizing a
multi-task learning approach where models for different languages have separate
output labels but share some internal parameters. In this work, we exploit
recent progress in end-to-end speech recognition to create a single
multilingual speech recognition system capable of recognizing any of the
languages seen in training. To do so, we propose the use of a universal
character set that is shared among all languages. We also create a
language-specific gating mechanism within the network that can modulate the
network's internal representations in a language-specific way. We evaluate our
proposed approach on the Microsoft Cortana task across three languages and show
that our system outperforms both the individual monolingual systems and systems
built with a multi-task learning approach. We also show that this model can be
used to initialize a monolingual speech recognizer, and can be used to create a
bilingual model for use in code-switching scenarios.