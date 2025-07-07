---
layout: publication
title: 'Normformer: Improved Transformer Pretraining With Extra Normalization'
authors: Sam Shleifer, Jason Weston, Myle Ott
conference: Arxiv
year: 2021
citations: 26
bibkey: shleifer2021improved
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.09456'}, {name: Code,
    url: 'https://github.com/pytorch/fairseq/tree/main/examples/normformer'}]
tags: [Masked Language Model, Training Techniques, Transformer, GPT, RAG, Reinforcement
    Learning, Attention Mechanism, BERT, Has Code, Language Modeling, Model Architecture]
---
During pretraining, the Pre-LayerNorm transformer suffers from a gradient
magnitude mismatch: gradients at early layers are much larger than at later
layers. These issues can be alleviated by our proposed NormFormer architecture,
which adds three normalization operations to each layer: a Layer Norm after
self attention, head-wise scaling of self-attention outputs, and a Layer Norm
after the first fully connected layer. The extra operations incur negligible
compute cost (+0.4% parameter increase), but improve pretraining perplexity and
downstream task performance for both causal and masked language models ranging
from 125 Million to 2.7 Billion parameters. For example, adding NormFormer on
top of our strongest 1.3B parameter baseline can reach equal perplexity 24%
faster, or converge 0.27 perplexity better in the same compute budget. This
model reaches GPT3-Large (1.3B) zero shot performance 60% faster. For masked
language modeling, NormFormer improves fine-tuned GLUE performance by 1.9% on
average. Code to train NormFormer models is available in fairseq
https://github.com/pytorch/fairseq/tree/main/examples/normformer .