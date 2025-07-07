---
layout: publication
title: 'UER: An Open-source Toolkit For Pre-training Models'
authors: Zhe Zhao et al.
conference: Arxiv
year: 2019
citations: 48
bibkey: zhao2019open
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.05658'}]
tags: [Training Techniques, Pre-Training, Tools, BERT, Model Architecture]
---
Existing works, including ELMO and BERT, have revealed the importance of
pre-training for NLP tasks. While there does not exist a single pre-training
model that works best in all cases, it is of necessity to develop a framework
that is able to deploy various pre-training models efficiently. For this
purpose, we propose an assemble-on-demand pre-training toolkit, namely
Universal Encoder Representations (UER). UER is loosely coupled, and
encapsulated with rich modules. By assembling modules on demand, users can
either reproduce a state-of-the-art pre-training model or develop a
pre-training model that remains unexplored. With UER, we have built a model
zoo, which contains pre-trained models based on different corpora, encoders,
and targets (objectives). With proper pre-trained models, we could achieve new
state-of-the-art results on a range of downstream datasets.