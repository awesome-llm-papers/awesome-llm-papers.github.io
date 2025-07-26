---
layout: publication
title: A Hybrid Convolutional Variational Autoencoder For Text Generation
authors: Stanislau Semeniuta, Aliaksei Severyn, Erhardt Barth
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: semeniuta2017hybrid
citations: 222
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1702.02390'}]
tags: ["EMNLP", "Model Architecture", "Training Techniques"]
short_authors: Stanislau Semeniuta, Aliaksei Severyn, Erhardt Barth
---
In this paper we explore the effect of architectural choices on learning a
Variational Autoencoder (VAE) for text generation. In contrast to the
previously introduced VAE model for text where both the encoder and decoder are
RNNs, we propose a novel hybrid architecture that blends fully feed-forward
convolutional and deconvolutional components with a recurrent language model.
Our architecture exhibits several attractive properties such as faster run time
and convergence, ability to better handle long sequences and, more importantly,
it helps to avoid some of the major difficulties posed by training VAE models
on textual data.