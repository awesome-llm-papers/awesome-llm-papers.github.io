---
layout: publication
title: Implicit Representations Of Meaning In Neural Language Models
authors: Belinda Z. Li, Maxwell Nye, Jacob Andreas
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: li2021implicit
citations: 65
additional_links: [{name: Code, url: 'https://github.com/belindal/state-probes'},
  {name: Paper, url: 'https://arxiv.org/abs/2106.00737'}]
tags: ["Model Architecture"]
short_authors: Belinda Z. Li, Maxwell Nye, Jacob Andreas
---
Does the effectiveness of neural language models derive entirely from
accurate modeling of surface word co-occurrence statistics, or do these models
represent and reason about the world they describe? In BART and T5 transformer
language models, we identify contextual word representations that function as
models of entities and situations as they evolve throughout a discourse. These
neural representations have functional similarities to linguistic models of
dynamic semantics: they support a linear readout of each entity's current
properties and relations, and can be manipulated with predictable effects on
language generation. Our results indicate that prediction in pretrained neural
language models is supported, at least in part, by dynamic representations of
meaning and implicit simulation of entity state, and that this behavior can be
learned with only text as training data. Code and data are available at
https://github.com/belindal/state-probes .