---
layout: publication
title: 'Demix Layers: Disentangling Domains For Modular Language Modeling'
authors: Suchin Gururangan, Mike Lewis, Ari Holtzman, Noah A. Smith, Luke Zettlemoyer
conference: 'Proceedings of the 2022 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
citations: 15
bibkey: gururangan2021demix
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.05036'}]
tags: [Language Modeling, Model Architecture, GPT, Transformer, Tools, Efficiency
    and Optimization, Training Techniques]
---
We introduce a new domain expert mixture (DEMix) layer that enables
conditioning a language model (LM) on the domain of the input text. A DEMix
layer is a collection of expert feedforward networks, each specialized to a
domain, that makes the LM modular: experts can be mixed, added or removed after
initial training. Extensive experiments with autoregressive transformer LMs (up
to 1.3B parameters) show that DEMix layers reduce test-time perplexity,
increase training efficiency, and enable rapid adaptation with little overhead.
We show that mixing experts during inference, using a parameter-free weighted
ensemble, allows the model to better generalize to heterogeneous or unseen
domains. We also show that experts can be added to iteratively incorporate new
domains without forgetting older ones, and that experts can be removed to
restrict access to unwanted domains, without additional training. Overall,
these results demonstrate benefits of explicitly conditioning on textual
domains during language modeling.