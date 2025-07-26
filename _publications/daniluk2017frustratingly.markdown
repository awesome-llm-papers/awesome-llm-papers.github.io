---
layout: publication
title: Frustratingly Short Attention Spans In Neural Language Modeling
authors: "Micha\u0142 Daniluk, Tim Rockt\xE4schel, Johannes Welbl, Sebastian Riedel"
conference: Arxiv
year: 2017
bibkey: daniluk2017frustratingly
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1702.04521'}]
tags: ["Model Architecture"]
short_authors: Daniluk et al.
---
Neural language models predict the next token using a latent representation
of the immediate token history. Recently, various methods for augmenting neural
language models with an attention mechanism over a differentiable memory have
been proposed. For predicting the next token, these models query information
from a memory of the recent history which can facilitate learning mid- and
long-range dependencies. However, conventional attention mechanisms used in
memory-augmented neural language models produce a single output vector per time
step. This vector is used both for predicting the next token as well as for the
key and value of a differentiable memory of a token history. In this paper, we
propose a neural language model with a key-value attention mechanism that
outputs separate representations for the key and value of a differentiable
memory, as well as for encoding the next-word distribution. This model
outperforms existing memory-augmented neural language models on two corpora.
Yet, we found that our method mainly utilizes a memory of the five most recent
output representations. This led to the unexpected main finding that a much
simpler model based only on the concatenation of recent output representations
from previous time steps is on par with more sophisticated memory-augmented
neural language models.