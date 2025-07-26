---
layout: publication
title: Neural Codec Language Models Are Zero-shot Text To Speech Synthesizers
authors: [chengyi Wang, sanyuan Chen, yu Wu, ziqiang Zhang, long Zhou, shujie Liu,
  zhuo Chen, yanqing Liu, huaming Wang, jinyu Li, lei He, sheng Zhao, furu Wei]
conference: Arxiv
year: 2023
bibkey: chengyi2023neural
citations: 141
additional_links: [{name: Code, url: 'https://aka.ms/valle'}, {name: Paper, url: 'http://arxiv.org/abs/2301.02111v1'}]
tags: ["In Context Learning", "Prompting", "Training Techniques"]
short_authors: Wang et al.
---
We introduce a language modeling approach for text to speech synthesis (TTS).
Specifically, we train a neural codec language model (called Vall-E) using
discrete codes derived from an off-the-shelf neural audio codec model, and
regard TTS as a conditional language modeling task rather than continuous
signal regression as in previous work. During the pre-training stage, we scale
up the TTS training data to 60K hours of English speech which is hundreds of
times larger than existing systems. Vall-E emerges in-context learning
capabilities and can be used to synthesize high-quality personalized speech
with only a 3-second enrolled recording of an unseen speaker as an acoustic
prompt. Experiment results show that Vall-E significantly outperforms the
state-of-the-art zero-shot TTS system in terms of speech naturalness and
speaker similarity. In addition, we find Vall-E could preserve the speaker's
emotion and acoustic environment of the acoustic prompt in synthesis. See
https://aka.ms/valle for demos of our work.