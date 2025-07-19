---
layout: publication
title: Better Prompt Compression Without Multi-layer Perceptrons
authors: Honig et al.
conference: Texts in Computer Science
year: 2025
bibkey: honig2025better
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.06730'}]
tags: [Attention Mechanism, Alt, Prompting, Transformer, Model Architecture, Fine
    Tuning]
---
Prompt compression is a promising approach to speeding up language model
inference without altering the generative model. Prior works compress prompts
into smaller sequences of learned tokens using an encoder that is trained as a
LowRank Adaptation (LoRA) of the inference language model. However, we show
that the encoder does not need to keep the original language model's
architecture to achieve useful compression. We introduce the Attention-Only
Compressor (AOC), which learns a prompt compression encoder after removing the
multilayer perceptron (MLP) layers in the Transformer blocks of a language
model, resulting in an encoder with roughly 67% less parameters compared to the
original model. Intriguingly we find that, across a range of compression ratios
up to 480x, AOC can better regenerate prompts and outperform a baseline
compression encoder that is a LoRA of the inference language model without
removing MLP layers. These results demonstrate that the architecture of prompt
compression encoders does not need to be identical to that of the original
decoder language model, paving the way for further research into architectures
and approaches for prompt compression.