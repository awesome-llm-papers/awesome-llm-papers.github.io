---
layout: publication
title: 'Fnetar: Mixing Tokens With Autoregressive Fourier Transforms'
authors: Lou et al.
conference: 'Proceedings of the 2022 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: lou2021fnetar
citations: 214
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.10932'}]
tags: [Model Architecture, Evaluation, ACL, Transformer, GPT, NAACL, Datasets, Language
    Modeling, Attention Mechanism]
---
In this note we examine the autoregressive generalization of the FNet
algorithm, in which self-attention layers from the standard Transformer
architecture are substituted with a trivial sparse-uniformsampling procedure
based on Fourier transforms. Using the Wikitext-103 benchmark, we
demonstratethat FNetAR retains state-of-the-art performance (25.8 ppl) on the
task of causal language modelingcompared to a Transformer-XL baseline (24.2
ppl) with only half the number self-attention layers,thus providing further
evidence for the superfluity of deep neural networks with heavily
compoundedattention mechanisms. The autoregressive Fourier transform could
likely be used for parameterreduction on most Transformer-based time-series
prediction models.