---
layout: publication
title: Reference-aware Language Models
authors: Yang et al.
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: yang2016reference
citations: 79
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.01628'}]
tags: [Model Architecture, Attention Mechanism, EMNLP]
---
We propose a general class of language models that treat reference as an
explicit stochastic latent variable. This architecture allows models to create
mentions of entities and their attributes by accessing external databases
(required by, e.g., dialogue generation and recipe generation) and internal
state (required by, e.g. language models which are aware of coreference). This
facilitates the incorporation of information that can be accessed in
predictable locations in databases or discourse context, even when the targets
of the reference may be rare words. Experiments on three tasks shows our model
variants based on deterministic attention.