---
layout: publication
title: Efficient Long-text Understanding With Short-text Models
authors: Maor Ivgi, Uri Shaham, Jonathan Berant
conference: Arxiv
year: 2022
citations: 16
bibkey: ivgi2022efficient
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2208.00748'}]
tags: [Training Techniques, Transformer, Merging, RAG, Reinforcement Learning, Model
    Architecture]
---
Transformer-based pretrained language models (LMs) are ubiquitous across
natural language understanding, but cannot be applied to long sequences such as
stories, scientific articles and long documents, due to their quadratic
complexity. While a myriad of efficient transformer variants have been
proposed, they are typically based on custom implementations that require
expensive pretraining from scratch. In this work, we propose SLED:
SLiding-Encoder and Decoder, a simple approach for processing long sequences
that re-uses and leverages battle-tested short-text pretrained LMs.
Specifically, we partition the input into overlapping chunks, encode each with
a short-text LM encoder and use the pretrained decoder to fuse information
across chunks (fusion-in-decoder). We illustrate through controlled experiments
that SLED offers a viable strategy for long text understanding and evaluate our
approach on SCROLLS, a benchmark with seven datasets across a wide range of
language understanding tasks. We find that SLED is competitive with specialized
models that are up to 50x larger and require a dedicated and expensive
pretraining step.