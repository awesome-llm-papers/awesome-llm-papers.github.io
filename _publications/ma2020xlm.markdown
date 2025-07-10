---
layout: publication
title: 'XLM-T: Scaling Up Multilingual Machine Translation With Pretrained Cross-lingual
  Transformer Encoders'
authors: Shuming Ma et al.
conference: Arxiv
year: 2020
citations: 22
bibkey: ma2020xlm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.15547'}, {name: Code,
    url: 'https://aka.ms/xlm-t'}]
tags: [Has Code, Model Architecture, Transformer, WMT, Pre-Training, Training Techniques]
---
Multilingual machine translation enables a single model to translate between
different languages. Most existing multilingual machine translation systems
adopt a randomly initialized Transformer backbone. In this work, inspired by
the recent success of language model pre-training, we present XLM-T, which
initializes the model with an off-the-shelf pretrained cross-lingual
Transformer encoder and fine-tunes it with multilingual parallel data. This
simple method achieves significant improvements on a WMT dataset with 10
language pairs and the OPUS-100 corpus with 94 pairs. Surprisingly, the method
is also effective even upon the strong baseline with back-translation.
Moreover, extensive analysis of XLM-T on unsupervised syntactic parsing, word
alignment, and multilingual classification explains its effectiveness for
machine translation. The code will be at https://aka.ms/xlm-t.