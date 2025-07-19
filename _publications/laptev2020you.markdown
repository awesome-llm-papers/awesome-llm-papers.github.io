---
layout: publication
title: 'You Do Not Need More Data: Improving End-to-end Speech Recognition By Text-to-speech
  Data Augmentation'
authors: Laptev et al.
conference: 2020 13th International Congress on Image and Signal Processing, BioMedical
  Engineering and Informatics (CISP-BMEI)
year: 2020
bibkey: laptev2020you
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.07157'}]
tags: [Training Techniques]
---
Data augmentation is one of the most effective ways to make end-to-end
automatic speech recognition (ASR) perform close to the conventional hybrid
approach, especially when dealing with low-resource tasks. Using recent
advances in speech synthesis (text-to-speech, or TTS), we build our TTS system
on an ASR training database and then extend the data with synthesized speech to
train a recognition model. We argue that, when the training data amount is
relatively low, this approach can allow an end-to-end model to reach hybrid
systems' quality. For an artificial low-to-medium-resource setup, we compare
the proposed augmentation with the semi-supervised learning technique. We also
investigate the influence of vocoder usage on final ASR performance by
comparing Griffin-Lim algorithm with our modified LPCNet. When applied with an
external language model, our approach outperforms a semi-supervised setup for
LibriSpeech test-clean and only 33% worse than a comparable supervised setup.
Our system establishes a competitive result for end-to-end ASR trained on
LibriSpeech train-clean-100 set with WER 4.3% for test-clean and 13.5% for
test-other.