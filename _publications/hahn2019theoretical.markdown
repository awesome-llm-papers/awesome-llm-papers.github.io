---
layout: publication
title: Theoretical Limitations Of Self-attention In Neural Sequence Models
authors: Michael Hahn
conference: Transactions of the Association for Computational Linguistics
year: 2020
bibkey: hahn2019theoretical
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.06755'}]
tags: ["Model Architecture", "TACL"]
short_authors: Michael Hahn
---
Transformers are emerging as the new workhorse of NLP, showing great success
across tasks. Unlike LSTMs, transformers process input sequences entirely
through self-attention. Previous work has suggested that the computational
capabilities of self-attention to process hierarchical structures are limited.
In this work, we mathematically investigate the computational power of
self-attention to model formal languages. Across both soft and hard attention,
we show strong theoretical limitations of the computational abilities of
self-attention, finding that it cannot model periodic finite-state languages,
nor hierarchical structure, unless the number of layers or heads increases with
input length. These limitations seem surprising given the practical success of
self-attention and the prominent role assigned to hierarchical structure in
linguistics, suggesting that natural language can be approximated well with
models that are too weak for the formal languages typically assumed in
theoretical linguistics.