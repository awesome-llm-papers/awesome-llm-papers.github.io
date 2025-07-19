---
layout: publication
title: Latent Normalizing Flows For Discrete Sequences
authors: Ziegler Zachary M., Rush Alexander M.
conference: Arxiv
year: 2019
bibkey: ziegler2019latent
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1901.10548'}]
tags: [Alt, Model Architecture, Multimodal Models, GPT]
---
Normalizing flows are a powerful class of generative models for continuous
random variables, showing both strong model flexibility and the potential for
non-autoregressive generation. These benefits are also desired when modeling
discrete random variables such as text, but directly applying normalizing flows
to discrete sequences poses significant additional challenges. We propose a
VAE-based generative model which jointly learns a normalizing flow-based
distribution in the latent space and a stochastic mapping to an observed
discrete space. In this setting, we find that it is crucial for the flow-based
distribution to be highly multimodal. To capture this property, we propose
several normalizing flow architectures to maximize model flexibility.
Experiments consider common discrete sequence tasks of character-level language
modeling and polyphonic music generation. Our results indicate that an
autoregressive flow-based model can match the performance of a comparable
autoregressive baseline, and a non-autoregressive flow-based model can improve
generation speed with a penalty to performance.