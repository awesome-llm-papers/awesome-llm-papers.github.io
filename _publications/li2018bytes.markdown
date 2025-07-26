---
layout: publication
title: 'Bytes Are All You Need: End-to-end Multilingual Speech Recognition And Synthesis
  With Bytes'
authors: Bo Li, Yu Zhang, Tara Sainath, Yonghui Wu, William Chan
conference: ICASSP 2019 - 2019 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2019
bibkey: li2018bytes
citations: 133
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.09021'}]
tags: ["ICASSP"]
short_authors: Li et al.
---
We present two end-to-end models: Audio-to-Byte (A2B) and Byte-to-Audio
(B2A), for multilingual speech recognition and synthesis. Prior work has
predominantly used characters, sub-words or words as the unit of choice to
model text. These units are difficult to scale to languages with large
vocabularies, particularly in the case of multilingual processing. In this
work, we model text via a sequence of Unicode bytes, specifically, the UTF-8
variable length byte sequence for each character. Bytes allow us to avoid large
softmaxes in languages with large vocabularies, and share representations in
multilingual models. We show that bytes are superior to grapheme characters
over a wide variety of languages in monolingual end-to-end speech recognition.
Additionally, our multilingual byte model outperform each respective single
language baseline on average by 4.4% relatively. In Japanese-English
code-switching speech, our multilingual byte model outperform our monolingual
baseline by 38.6% relatively. Finally, we present an end-to-end multilingual
speech synthesis model using byte representations which matches the performance
of our monolingual baselines.