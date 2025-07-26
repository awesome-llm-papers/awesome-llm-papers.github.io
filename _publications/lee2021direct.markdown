---
layout: publication
title: Direct Speech-to-speech Translation With Discrete Units
authors: Ann Lee, Peng-jen Chen, Changhan Wang, Jiatao Gu, Sravya Popuri, Xutai Ma,
  Adam Polyak, Yossi Adi, Qing He, Yun Tang, Juan Pino, Wei-ning Hsu
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: lee2021direct
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.05604'}]
tags: ["Has Code", "Tools"]
short_authors: Lee et al.
---
We present a direct speech-to-speech translation (S2ST) model that translates
speech from one language to speech in another language without relying on
intermediate text generation. We tackle the problem by first applying a
self-supervised discrete speech encoder on the target speech and then training
a sequence-to-sequence speech-to-unit translation (S2UT) model to predict the
discrete representations of the target speech. When target text transcripts are
available, we design a joint speech and text training framework that enables
the model to generate dual modality output (speech and text) simultaneously in
the same inference pass. Experiments on the Fisher Spanish-English dataset show
that the proposed framework yields improvement of 6.7 BLEU compared with a
baseline direct S2ST model that predicts spectrogram features. When trained
without any text transcripts, our model performance is comparable to models
that predict spectrograms and are trained with text supervision, showing the
potential of our system for translation between unwritten languages. Audio
samples are available at
https://facebookresearch.github.io/speech_translation/direct_s2st_units/index.html .