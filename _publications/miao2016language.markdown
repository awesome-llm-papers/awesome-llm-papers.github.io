---
layout: publication
title: 'Language As A Latent Variable: Discrete Generative Models For Sentence Compression'
authors: Yishu Miao, Phil Blunsom
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: miao2016language
citations: 195
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1609.07317'}]
tags: ["EMNLP"]
short_authors: Yishu Miao, Phil Blunsom
---
In this work we explore deep generative models of text in which the latent
representation of a document is itself drawn from a discrete language model
distribution. We formulate a variational auto-encoder for inference in this
model and apply it to the task of compressing sentences. In this application
the generative model first draws a latent summary sentence from a background
language model, and then subsequently draws the observed sentence conditioned
on this latent summary. In our empirical evaluation we show that generative
formulations of both abstractive and extractive compression yield
state-of-the-art results when trained on a large amount of supervised data.
Further, we explore semi-supervised compression scenarios where we show that it
is possible to achieve performance competitive with previously proposed
supervised models while training on a fraction of the supervised data.