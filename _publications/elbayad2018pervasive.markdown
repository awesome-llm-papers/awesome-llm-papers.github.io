---
layout: publication
title: 'Pervasive Attention: 2D Convolutional Neural Networks For Sequence-to-sequence
  Prediction'
authors: Elbayad Maha, Besacier Laurent, Verbeek Jakob
conference: Arxiv
year: 2018
bibkey: elbayad2018pervasive
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.03867'}]
tags: [Attention Mechanism, Alt, Transformer, Model Architecture, Language Modeling]
---
Current state-of-the-art machine translation systems are based on
encoder-decoder architectures, that first encode the input sequence, and then
generate an output sequence based on the input encoding. Both are interfaced
with an attention mechanism that recombines a fixed encoding of the source
tokens based on the decoder state. We propose an alternative approach which
instead relies on a single 2D convolutional neural network across both
sequences. Each layer of our network re-codes source tokens on the basis of the
output sequence produced so far. Attention-like properties are therefore
pervasive throughout the network. Our model yields excellent results,
outperforming state-of-the-art encoder-decoder systems, while being
conceptually simpler and having fewer parameters.