---
layout: publication
title: A Hierarchical Latent Structure For Variational Conversation Modeling
authors: Yookoon Park, Jaemin Cho, Gunhee Kim
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 1
  (Long Papers)'
year: 2018
bibkey: park2018hierarchical
citations: 109
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.03424'}]
tags: ["NAACL"]
short_authors: Yookoon Park, Jaemin Cho, Gunhee Kim
---
Variational autoencoders (VAE) combined with hierarchical RNNs have emerged
as a powerful framework for conversation modeling. However, they suffer from
the notorious degeneration problem, where the decoders learn to ignore latent
variables and reduce to vanilla RNNs. We empirically show that this degeneracy
occurs mostly due to two reasons. First, the expressive power of hierarchical
RNN decoders is often high enough to model the data using only its decoding
distributions without relying on the latent variables. Second, the conditional
VAE structure whose generation process is conditioned on a context, makes the
range of training targets very sparse; that is, the RNN decoders can easily
overfit to the training data ignoring the latent variables. To solve the
degeneration problem, we propose a novel model named Variational Hierarchical
Conversation RNNs (VHCR), involving two key ideas of (1) using a hierarchical
structure of latent variables, and (2) exploiting an utterance drop
regularization. With evaluations on two datasets of Cornell Movie Dialog and
Ubuntu Dialog Corpus, we show that our VHCR successfully utilizes latent
variables and outperforms state-of-the-art models for conversation generation.
Moreover, it can perform several new utterance control tasks, thanks to its
hierarchical latent structure.