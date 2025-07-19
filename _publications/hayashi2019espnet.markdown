---
layout: publication
title: 'Espnet-tts: Unified, Reproducible, And Integratable Open Source End-to-end
  Text-to-speech Toolkit'
authors: Hayashi et al.
conference: ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2019
bibkey: hayashi2019espnet
citations: 91
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.10909'}]
tags: [Training Techniques, Evaluation, Transformer, ICASSP, Model Architecture, Reinforcement
    Learning, Datasets]
---
This paper introduces a new end-to-end text-to-speech (E2E-TTS) toolkit named
ESPnet-TTS, which is an extension of the open-source speech processing toolkit
ESPnet. The toolkit supports state-of-the-art E2E-TTS models, including
Tacotron~2, Transformer TTS, and FastSpeech, and also provides recipes inspired
by the Kaldi automatic speech recognition (ASR) toolkit. The recipes are based
on the design unified with the ESPnet ASR recipe, providing high
reproducibility. The toolkit also provides pre-trained models and samples of
all of the recipes so that users can use it as a baseline. Furthermore, the
unified design enables the integration of ASR functions with TTS, e.g.,
ASR-based objective evaluation and semi-supervised learning with both ASR and
TTS models. This paper describes the design of the toolkit and experimental
evaluation in comparison with other toolkits. The experimental results show
that our models can achieve state-of-the-art performance comparable to the
other latest toolkits, resulting in a mean opinion score (MOS) of 4.25 on the
LJSpeech dataset. The toolkit is publicly available at
https://github.com/espnet/espnet.