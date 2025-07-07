---
layout: publication
title: 'Logic2text: High-fidelity Natural Language Generation From Logical Forms'
authors: Zhiyu Chen et al.
conference: Arxiv
year: 2020
citations: 18
bibkey: chen2020high
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.14579'}, {name: Code,
    url: 'https://github.com/czyssrs/Logic2Text'}]
tags: [Training Techniques, RAG, Few-Shot, Reinforcement Learning, Has Code]
---
Previous works on Natural Language Generation (NLG) from structured data have
primarily focused on surface-level descriptions of record sequences. However,
for complex structured data, e.g., multi-row tables, it is often desirable for
an NLG system to describe interesting facts from logical inferences across
records. If only provided with the table, it is hard for existing models to
produce controllable and high-fidelity logical generations. In this work, we
formulate logical level NLG as generation from logical forms in order to obtain
controllable, high-fidelity, and faithful generations. We present a new
large-scale dataset, \textsc\{Logic2Text\}, with 10,753 descriptions involving
common logic types paired with the underlying logical forms. The logical forms
show diversified graph structure of free schema, which poses great challenges
on the model's ability to understand the semantics. We experiment on (1)
Fully-supervised training with the full datasets, and (2) Few-shot setting,
provided with hundreds of paired examples; We compare several popular
generation models and analyze their performances. We hope our dataset can
encourage research towards building an advanced NLG system capable of natural,
faithful, and human-like generation. The dataset and code are available at
https://github.com/czyssrs/Logic2Text.