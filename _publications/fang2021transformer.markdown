---
layout: publication
title: Transformer-based Conditional Variational Autoencoder For Controllable Story
  Generation
authors: Le Fang et al.
conference: Arxiv
year: 2021
citations: 40
bibkey: fang2021transformer
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2101.00828'}]
tags: [GPT, Transformer, Model Architecture]
---
We investigate large-scale latent variable models (LVMs) for neural story
generation -- an under-explored application for open-domain long text -- with
objectives in two threads: generation effectiveness and controllability. LVMs,
especially the variational autoencoder (VAE), have achieved both effective and
controllable generation through exploiting flexible distributional latent
representations. Recently, Transformers and its variants have achieved
remarkable effectiveness without explicit latent representation learning, thus
lack satisfying controllability in generation. In this paper, we advocate to
revive latent variable modeling, essentially the power of representation
learning, in the era of Transformers to enhance controllability without hurting
state-of-the-art generation effectiveness. Specifically, we integrate latent
representation vectors with a Transformer-based pre-trained architecture to
build conditional variational autoencoder (CVAE). Model components such as
encoder, decoder and the variational posterior are all built on top of
pre-trained language models -- GPT2 specifically in this paper. Experiments
demonstrate state-of-the-art conditional generation ability of our model, as
well as its excellent representation learning capability and controllability.