---
layout: publication
title: A Convolutional Attention Network For Extreme Summarization Of Source Code
authors: Allamanis Miltiadis, Peng Hao, Sutton Charles
conference: Arxiv
year: 2016
bibkey: allamanis2016convolutional
citations: 358
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1602.03001'}]
tags: [Model Architecture, Attention Mechanism, Transformer]
---
Attention mechanisms in neural networks have proved useful for problems in
which the input and output do not have fixed dimension. Often there exist
features that are locally translation invariant and would be valuable for
directing the model's attention, but previous attentional architectures are not
constructed to learn such features specifically. We introduce an attentional
neural network that employs convolution on the input tokens to detect local
time-invariant and long-range topical attention features in a context-dependent
way. We apply this architecture to the problem of extreme summarization of
source code snippets into short, descriptive function name-like summaries.
Using those features, the model sequentially generates a summary by
marginalizing over two attention mechanisms: one that predicts the next summary
token based on the attention weights of the input tokens and another that is
able to copy a code token as-is directly into the summary. We demonstrate our
convolutional attention neural network's performance on 10 popular Java
projects showing that it achieves better performance compared to previous
attentional mechanisms.