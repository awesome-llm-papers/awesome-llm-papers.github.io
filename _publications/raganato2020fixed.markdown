---
layout: publication
title: Fixed Encoder Self-attention Patterns In Transformer-based Machine Translation
authors: "Alessandro Raganato, Yves Scherrer, J\xF6rg Tiedemann"
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: raganato2020fixed
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2002.10260'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: "Alessandro Raganato, Yves Scherrer, J\xF6rg Tiedemann"
---
Transformer-based models have brought a radical change to neural machine
translation. A key feature of the Transformer architecture is the so-called
multi-head attention mechanism, which allows the model to focus simultaneously
on different parts of the input. However, recent works have shown that most
attention heads learn simple, and often redundant, positional patterns. In this
paper, we propose to replace all but one attention head of each encoder layer
with simple fixed -- non-learnable -- attentive patterns that are solely based
on position and do not require any external knowledge. Our experiments with
different data sizes and multiple language pairs show that fixing the attention
heads on the encoder side of the Transformer at training time does not impact
the translation quality and even increases BLEU scores by up to 3 points in
low-resource scenarios.