---
layout: publication
title: 'Minicons: Enabling Flexible Behavioral And Representational Analyses Of Transformer
  Language Models'
authors: Kanishka Misra
conference: Arxiv
year: 2022
citations: 23
bibkey: misra2022enabling
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.13112'}, {name: Code,
    url: 'https://github.com/kanishkamisra/minicons'}]
tags: [Transformer, Tools, BERT, Has Code, Model Architecture]
---
We present minicons, an open source library that provides a standard API for
researchers interested in conducting behavioral and representational analyses
of transformer-based language models (LMs). Specifically, minicons enables
researchers to apply analysis methods at two levels: (1) at the prediction
level -- by providing functions to efficiently extract word/sentence level
probabilities; and (2) at the representational level -- by also facilitating
efficient extraction of word/phrase level vectors from one or more layers. In
this paper, we describe the library and apply it to two motivating case
studies: One focusing on the learning dynamics of the BERT architecture on
relative grammatical judgments, and the other on benchmarking 23 different LMs
on zero-shot abductive reasoning. minicons is available at
https://github.com/kanishkamisra/minicons