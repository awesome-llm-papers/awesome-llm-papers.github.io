---
layout: publication
title: Generating Sentences By Editing Prototypes
authors: Kelvin Guu, Tatsunori B. Hashimoto, Yonatan Oren, Percy Liang
conference: Transactions of the Association for Computational Linguistics
year: 2018
bibkey: guu2017generating
citations: 306
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1709.08878'}]
tags: ["TACL"]
short_authors: Guu et al.
---
We propose a new generative model of sentences that first samples a prototype
sentence from the training corpus and then edits it into a new sentence.
Compared to traditional models that generate from scratch either left-to-right
or by first sampling a latent sentence vector, our prototype-then-edit model
improves perplexity on language modeling and generates higher quality outputs
according to human evaluation. Furthermore, the model gives rise to a latent
edit vector that captures interpretable semantics such as sentence similarity
and sentence-level analogies.