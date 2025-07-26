---
layout: publication
title: 'Fastpitch: Parallel Text-to-speech With Pitch Prediction'
authors: "Adrian \u0141a\u0144cucki"
conference: ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2021
bibkey: "\u0142a\u0144cucki2020fastpitch"
citations: 184
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.06873'}]
tags: ["ICASSP"]
short_authors: "Adrian \u0141a\u0144cucki"
---
We present FastPitch, a fully-parallel text-to-speech model based on
FastSpeech, conditioned on fundamental frequency contours. The model predicts
pitch contours during inference. By altering these predictions, the generated
speech can be more expressive, better match the semantic of the utterance, and
in the end more engaging to the listener. Uniformly increasing or decreasing
pitch with FastPitch generates speech that resembles the voluntary modulation
of voice. Conditioning on frequency contours improves the overall quality of
synthesized speech, making it comparable to state-of-the-art. It does not
introduce an overhead, and FastPitch retains the favorable, fully-parallel
Transformer architecture, with over 900x real-time factor for mel-spectrogram
synthesis of a typical utterance.