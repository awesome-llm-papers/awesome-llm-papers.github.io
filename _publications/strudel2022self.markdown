---
layout: publication
title: Self-conditioned Embedding Diffusion For Text Generation
authors: Robin Strudel et al.
conference: Arxiv
year: 2022
citations: 18
bibkey: strudel2022self
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.04236'}]
tags: [Language Modeling, Reinforcement Learning, GPT, Evaluation, Merging]
---
Can continuous diffusion models bring the same performance breakthrough on
natural language they did for image generation? To circumvent the discrete
nature of text data, we can simply project tokens in a continuous space of
embeddings, as is standard in language modeling. We propose Self-conditioned
Embedding Diffusion, a continuous diffusion mechanism that operates on token
embeddings and allows to learn flexible and scalable diffusion models for both
conditional and unconditional text generation. Through qualitative and
quantitative evaluation, we show that our text diffusion models generate
samples comparable with those produced by standard autoregressive language
models - while being in theory more efficient on accelerator hardware at
inference time. Our work paves the way for scaling up diffusion models for
text, similarly to autoregressive models, and for improving performance with
recent refinements to continuous diffusion.