---
layout: publication
title: Positional Encoding To Control Output Sequence Length
authors: Sho Takase, Naoaki Okazaki
conference: Proceedings of the 2019 Conference of the North
year: 2019
bibkey: takase2019positional
citations: 88
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.07418'}]
tags: ["Training Techniques"]
short_authors: Sho Takase, Naoaki Okazaki
---
Neural encoder-decoder models have been successful in natural language
generation tasks. However, real applications of abstractive summarization must
consider additional constraint that a generated summary should not exceed a
desired length. In this paper, we propose a simple but effective extension of a
sinusoidal positional encoding (Vaswani et al., 2017) to enable neural
encoder-decoder model to preserves the length constraint. Unlike in previous
studies where that learn embeddings representing each length, the proposed
method can generate a text of any length even if the target length is not
present in training data. The experimental results show that the proposed
method can not only control the generation length but also improve the ROUGE
scores.