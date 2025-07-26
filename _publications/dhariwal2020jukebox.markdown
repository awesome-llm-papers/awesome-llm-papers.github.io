---
layout: publication
title: 'Jukebox: A Generative Model For Music'
authors: Prafulla Dhariwal, Heewoo Jun, Christine Payne, Jong Wook Kim, Alec Radford,
  Ilya Sutskever
conference: Arxiv
year: 2020
bibkey: dhariwal2020jukebox
citations: 231
additional_links: [{name: Code, url: 'https://jukebox.openai.com,'}, {name: Code,
    url: 'https://github.com/openai/jukebox'}, {name: Paper, url: 'https://arxiv.org/abs/2005.00341'}]
tags: ["Has Code"]
short_authors: Dhariwal et al.
---
We introduce Jukebox, a model that generates music with singing in the raw
audio domain. We tackle the long context of raw audio using a multi-scale
VQ-VAE to compress it to discrete codes, and modeling those using
autoregressive Transformers. We show that the combined model at scale can
generate high-fidelity and diverse songs with coherence up to multiple minutes.
We can condition on artist and genre to steer the musical and vocal style, and
on unaligned lyrics to make the singing more controllable. We are releasing
thousands of non cherry-picked samples at https://jukebox.openai.com, along
with model weights and code at https://github.com/openai/jukebox