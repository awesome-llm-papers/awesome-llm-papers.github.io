---
layout: publication
title: Non-autoregressive Machine Translation With Disentangled Context Transformer
authors: Jungo Kasai, James Cross, Marjan Ghazvininejad, Jiatao Gu
conference: Arxiv
year: 2020
citations: 51
bibkey: kasai2020non
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2001.05136'}, {name: Code,
    url: 'https://github.com/facebookresearch/DisCo'}]
tags: [Has Code, Model Architecture, Attention Mechanism, Transformer, RAG, GPT]
---
State-of-the-art neural machine translation models generate a translation
from left to right and every step is conditioned on the previously generated
tokens. The sequential nature of this generation process causes fundamental
latency in inference since we cannot generate multiple tokens in each sentence
in parallel. We propose an attention-masking based model, called Disentangled
Context (DisCo) transformer, that simultaneously generates all tokens given
different contexts. The DisCo transformer is trained to predict every output
token given an arbitrary subset of the other reference tokens. We also develop
the parallel easy-first inference algorithm, which iteratively refines every
token in parallel and reduces the number of required iterations. Our extensive
experiments on 7 translation directions with varying data sizes demonstrate
that our model achieves competitive, if not better, performance compared to the
state of the art in non-autoregressive machine translation while significantly
reducing decoding time on average. Our code is available at
https://github.com/facebookresearch/DisCo.