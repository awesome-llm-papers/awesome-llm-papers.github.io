---
layout: publication
title: 'Gemma 2: Improving Open Language Models At A Practical Size'
authors: Gemma Team et al.
conference: Arxiv
year: 2024
citations: 35
bibkey: gemmateam2024gemma
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2408.00118'}]
tags: [Model Architecture, Attention Mechanism, Distillation, Transformer, Reinforcement
    Learning, Efficiency and Optimization]
---
In this work, we introduce Gemma 2, a new addition to the Gemma family of
lightweight, state-of-the-art open models, ranging in scale from 2 billion to
27 billion parameters. In this new version, we apply several known technical
modifications to the Transformer architecture, such as interleaving
local-global attentions (Beltagy et al., 2020a) and group-query attention
(Ainslie et al., 2023). We also train the 2B and 9B models with knowledge
distillation (Hinton et al., 2015) instead of next token prediction. The
resulting models deliver the best performance for their size, and even offer
competitive alternatives to models that are 2-3 times bigger. We release all
our models to the community.