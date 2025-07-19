---
layout: publication
title: Measuring Intrinsic Dimension Of Token Embeddings
authors: Kataiwa Takuya, Hakaze Cho, Ohki Tetsushi
conference: Physics Letters A
year: 2025
bibkey: kataiwa2025measuring
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.02142'}]
tags: [Fine Tuning, Tools, Training Techniques, Reinforcement Learning]
---
In this study, we measure the Intrinsic Dimension (ID) of token embedding to
estimate the intrinsic dimensions of the manifolds spanned by the
representations, so as to evaluate their redundancy quantitatively compared to
their extrinsic dimensionality. In detail, (1) we estimate the ID of token
embeddings in small-scale language models and also modern large language
models, finding that the embedding spaces often reside on lower-dimensional
manifolds compared to their extrinsic dimensionality; (2) we measure the ID
across various model sizes and observe an increase in redundancy rates as the
model scale grows; (3) we measure the dynamics of IDs during the training
process, and find a rapid ID drop in the early stages of training. Moreover,
(4) when LoRA is applied to the embedding layers, we observe a sudden drop in
perplexity around the estimated IDs, suggesting that the ID can serve as a
useful guideline for LoRA application.