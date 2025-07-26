---
layout: publication
title: 'Byt5: Towards A Token-free Future With Pre-trained Byte-to-byte Models'
authors: Linting Xue, Aditya Barua, Noah Constant, Rami Al-rfou, Sharan Narang, Mihir
  Kale, Adam Roberts, Colin Raffel
conference: Transactions of the Association for Computational Linguistics
year: 2022
bibkey: xue2021byt5
citations: 161
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.13626'}]
tags: ["Model Architecture", "TACL", "Training Techniques"]
short_authors: Xue et al.
---
Most widely-used pre-trained language models operate on sequences of tokens
corresponding to word or subword units. By comparison, token-free models that
operate directly on raw text (bytes or characters) have many benefits: they can
process text in any language out of the box, they are more robust to noise, and
they minimize technical debt by removing complex and error-prone text
preprocessing pipelines. Since byte or character sequences are longer than
token sequences, past work on token-free models has often introduced new model
architectures designed to amortize the cost of operating directly on raw text.
In this paper, we show that a standard Transformer architecture can be used
with minimal modifications to process byte sequences. We characterize the
trade-offs in terms of parameter count, training FLOPs, and inference speed,
and show that byte-level models are competitive with their token-level
counterparts. We also demonstrate that byte-level models are significantly more
robust to noise and perform better on tasks that are sensitive to spelling and
pronunciation. As part of our contribution, we release a new set of pre-trained
byte-level Transformer models based on the T5 architecture, as well as all code
and data used in our experiments.