---
layout: publication
title: 'THUMT: An Open Source Toolkit For Neural Machine Translation'
authors: Zhang et al.
conference: Arxiv
year: 2017
bibkey: zhang2017thumt
citations: 88
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1706.06415'}]
tags: [Training Techniques, Attention Mechanism, Tools, Model Architecture, Reinforcement
    Learning, Datasets]
---
This paper introduces THUMT, an open-source toolkit for neural machine
translation (NMT) developed by the Natural Language Processing Group at
Tsinghua University. THUMT implements the standard attention-based
encoder-decoder framework on top of Theano and supports three training
criteria: maximum likelihood estimation, minimum risk training, and
semi-supervised training. It features a visualization tool for displaying the
relevance between hidden states in neural networks and contextual words, which
helps to analyze the internal workings of NMT. Experiments on Chinese-English
datasets show that THUMT using minimum risk training significantly outperforms
GroundHog, a state-of-the-art toolkit for NMT.