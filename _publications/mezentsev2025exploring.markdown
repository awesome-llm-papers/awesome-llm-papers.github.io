---
layout: publication
title: Exploring The Latent Capacity Of Llms For One-step Text Generation
authors: Gleb Mezentsev, Ivan Oseledets
conference: No Venue
year: 2025
bibkey: mezentsev2025exploring
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6836babe75a4c5486bac4170'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.21189'}]
tags: []
short_authors: Gleb Mezentsev, Ivan Oseledets
---
A recent study showed that large language models (LLMs) can reconstruct surprisingly long texts - up to thousands of tokens - via autoregressive generation from just one specially trained input embedding. In this work, we explore whether such reconstruction is possible without autoregression. We show that frozen LLMs can generate hundreds of accurate tokens in just one forward pass, when provided with only two learned embeddings. This reveals a surprising and underexplored capability of LLMs - multi-token generation without iterative decoding. We investigate the behaviour of these embeddings and provide insight into the type of information they encode. We also empirically show that although these representations are not unique for a given text, they form connected and local regions in embedding space - a property that suggests the potential of learning a dedicated encoder into that space.

https://huggingface.co/discussions/paper/6836babe75a4c5486bac4170