---
layout: publication
title: Multiscale Sequence Modeling With A Learned Dictionary
authors: van et al.
conference: Neurocomputing
year: 2017
bibkey: "vanmerri\xEBnboer2017multiscale"
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.00762'}]
tags: [Model Architecture, Time Series, Language Modeling, Reinforcement Learning]
---
We propose a generalization of neural network sequence models. Instead of
predicting one symbol at a time, our multi-scale model makes predictions over
multiple, potentially overlapping multi-symbol tokens. A variation of the
byte-pair encoding (BPE) compression algorithm is used to learn the dictionary
of tokens that the model is trained with. When applied to language modelling,
our model has the flexibility of character-level models while maintaining many
of the performance benefits of word-level models. Our experiments show that
this model performs better than a regular LSTM on language modeling tasks,
especially for smaller models.