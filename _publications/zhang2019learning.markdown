---
layout: publication
title: 'Learning To Speak Fluently In A Foreign Language: Multilingual Speech Synthesis
  And Cross-language Voice Cloning'
authors: Zhang et al.
conference: Interspeech 2019
year: 2019
bibkey: zhang2019learning
citations: 149
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1907.04448'}]
tags: [RAG, Training Techniques, Attention Mechanism, INTERSPEECH, Model Architecture,
  Security]
---
We present a multispeaker, multilingual text-to-speech (TTS) synthesis model
based on Tacotron that is able to produce high quality speech in multiple
languages. Moreover, the model is able to transfer voices across languages,
e.g. synthesize fluent Spanish speech using an English speaker's voice, without
training on any bilingual or parallel examples. Such transfer works across
distantly related languages, e.g. English and Mandarin.
  Critical to achieving this result are: 1. using a phonemic input
representation to encourage sharing of model capacity across languages, and 2.
incorporating an adversarial loss term to encourage the model to disentangle
its representation of speaker identity (which is perfectly correlated with
language in the training data) from the speech content. Further scaling up the
model by training on multiple speakers of each language, and incorporating an
autoencoding input to help stabilize attention during training, results in a
model which can be used to consistently synthesize intelligible speech for
training speakers in all languages seen during training, and in native or
foreign accents.