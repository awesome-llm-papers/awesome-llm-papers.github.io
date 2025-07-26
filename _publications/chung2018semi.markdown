---
layout: publication
title: Semi-supervised Training For Improving Data Efficiency In End-to-end Speech
  Synthesis
authors: Yu-an Chung, Yuxuan Wang, Wei-ning Hsu, Yu Zhang, Rj Skerry-ryan
conference: ICASSP 2019 - 2019 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2019
bibkey: chung2018semi
citations: 97
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.10128'}]
tags: ["ICASSP", "Training Techniques"]
short_authors: Chung et al.
---
Although end-to-end text-to-speech (TTS) models such as Tacotron have shown
excellent results, they typically require a sizable set of high-quality <text,
audio> pairs for training, which are expensive to collect. In this paper, we
propose a semi-supervised training framework to improve the data efficiency of
Tacotron. The idea is to allow Tacotron to utilize textual and acoustic
knowledge contained in large, publicly-available text and speech corpora.
Importantly, these external data are unpaired and potentially noisy.
Specifically, first we embed each word in the input text into word vectors and
condition the Tacotron encoder on them. We then use an unpaired speech corpus
to pre-train the Tacotron decoder in the acoustic domain. Finally, we fine-tune
the model using available paired data. We demonstrate that the proposed
framework enables Tacotron to generate intelligible speech using less than half
an hour of paired training data.