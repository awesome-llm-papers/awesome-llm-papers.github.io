---
layout: publication
title: 'Encode, Tag, Realize: High-precision Text Editing'
authors: Eric Malmi, Sebastian Krause, Sascha Rothe, Daniil Mirylenka, Aliaksei Severyn
conference: Arxiv
year: 2019
citations: 40
bibkey: malmi2019high
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.01187'}]
tags: [Training Techniques, Transformer, GPT, Merging, BERT, Model Architecture]
---
We propose LaserTagger - a sequence tagging approach that casts text
generation as a text editing task. Target texts are reconstructed from the
inputs using three main edit operations: keeping a token, deleting it, and
adding a phrase before the token. To predict the edit operations, we propose a
novel model, which combines a BERT encoder with an autoregressive Transformer
decoder. This approach is evaluated on English text on four tasks: sentence
fusion, sentence splitting, abstractive summarization, and grammar correction.
LaserTagger achieves new state-of-the-art results on three of these tasks,
performs comparably to a set of strong seq2seq baselines with a large number of
training examples, and outperforms them when the number of examples is limited.
Furthermore, we show that at inference time tagging can be more than two orders
of magnitude faster than comparable seq2seq models, making it more attractive
for running in a live environment.