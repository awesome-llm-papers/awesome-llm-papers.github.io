---
layout: publication
title: 'K2: A Foundation Language Model For Geoscience Knowledge Understanding And
  Utilization'
authors: Cheng Deng et al.
conference: Arxiv
year: 2023
citations: 29
bibkey: deng2023foundation
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.05064'}, {name: Code,
    url: 'https://github.com/davendw49/k2'}]
tags: [Has Code, Applications, Tools, Training Techniques]
---
Large language models (LLMs) have achieved great success in general domains
of natural language processing. In this paper, we bring LLMs to the realm of
geoscience with the objective of advancing research and applications in this
field. To this end, we present the first-ever LLM in geoscience, K2, alongside
a suite of resources developed to further promote LLM research within
geoscience. For instance, we have curated the first geoscience instruction
tuning dataset, GeoSignal, which aims to align LLM responses to
geoscience-related user queries. Additionally, we have established the first
geoscience benchmark, GeoBench, to evaluate LLMs in the context of geoscience.
In this work, we experiment with a complete recipe to adapt a pre-trained
general-domain LLM to the geoscience domain. Specifically, we further train the
LLaMA-7B model on 5.5B tokens of geoscience text corpus, including over 1
million pieces of geoscience literature, and utilize GeoSignal's supervised
data to fine-tune the model. Moreover, we share a protocol that can efficiently
gather domain-specific data and construct domain-supervised data, even in
situations where manpower is scarce. Meanwhile, we equip K2 with the abilities
of using tools to be a naive geoscience aide. Experiments conducted on the
GeoBench demonstrate the effectiveness of our approach and datasets on
geoscience knowledge understanding and utilization.We open-source all the
training data and K2 model checkpoints at https://github.com/davendw49/k2.