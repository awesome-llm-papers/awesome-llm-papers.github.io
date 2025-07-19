---
layout: publication
title: What All Do Audio Transformer Models Hear? Probing Acoustic Representations
  For Language Delivery And Its Structure
authors: Shah et al.
conference: Arxiv
year: 2021
bibkey: shah2021what
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2101.00387'}]
tags: [Alt, Transformer, BERT, Model Architecture, Datasets]
---
In recent times, BERT based transformer models have become an inseparable
part of the 'tech stack' of text processing models. Similar progress is being
observed in the speech domain with a multitude of models observing
state-of-the-art results by using audio transformer models to encode speech.
This begs the question of what are these audio transformer models learning.
Moreover, although the standard methodology is to choose the last layer
embedding for any downstream task, but is it the optimal choice? We try to
answer these questions for the two recent audio transformer models, Mockingjay
and wave2vec2.0. We compare them on a comprehensive set of language delivery
and structure features including audio, fluency and pronunciation features.
Additionally, we probe the audio models' understanding of textual surface,
syntax, and semantic features and compare them to BERT. We do this over
exhaustive settings for native, non-native, synthetic, read and spontaneous
speech datasets