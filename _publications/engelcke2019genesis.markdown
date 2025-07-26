---
layout: publication
title: 'GENESIS: Generative Scene Inference And Sampling With Object-centric Latent
  Representations'
authors: Martin Engelcke, Adam R. Kosiorek, Oiwi Parker Jones, Ingmar Posner
conference: Arxiv
year: 2020
bibkey: engelcke2019genesis
citations: 79
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1907.13052'}]
tags: ["Tools"]
short_authors: Engelcke et al.
---
Generative latent-variable models are emerging as promising tools in robotics
and reinforcement learning. Yet, even though tasks in these domains typically
involve distinct objects, most state-of-the-art generative models do not
explicitly capture the compositional nature of visual scenes. Two recent
exceptions, MONet and IODINE, decompose scenes into objects in an unsupervised
fashion. Their underlying generative processes, however, do not account for
component interactions. Hence, neither of them allows for principled sampling
of novel scenes. Here we present GENESIS, the first object-centric generative
model of 3D visual scenes capable of both decomposing and generating scenes by
capturing relationships between scene components. GENESIS parameterises a
spatial GMM over images which is decoded from a set of object-centric latent
variables that are either inferred sequentially in an amortised fashion or
sampled from an autoregressive prior. We train GENESIS on several publicly
available datasets and evaluate its performance on scene generation,
decomposition, and semi-supervised learning.