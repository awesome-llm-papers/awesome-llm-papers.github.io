---
layout: publication
title: Variational Transformers For Diverse Response Generation
authors: Zhaojiang Lin, Genta Indra Winata, Peng Xu, Zihan Liu, Pascale Fung
conference: Arxiv
year: 2020
citations: 45
bibkey: lin2020variational
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.12738'}]
tags: [Model Architecture, GPT, Transformer, Efficiency and Optimization, Training
    Techniques, Time Series, Evaluation]
---
Despite the great promise of Transformers in many sequence modeling tasks
(e.g., machine translation), their deterministic nature hinders them from
generalizing to high entropy tasks such as dialogue response generation.
Previous work proposes to capture the variability of dialogue responses with a
recurrent neural network (RNN)-based conditional variational autoencoder
(CVAE). However, the autoregressive computation of the RNN limits the training
efficiency. Therefore, we propose the Variational Transformer (VT), a
variational self-attentive feed-forward sequence model. The VT combines the
parallelizability and global receptive field of the Transformer with the
variational nature of the CVAE by incorporating stochastic latent variables
into Transformers. We explore two types of the VT: 1) modeling the
discourse-level diversity with a global latent variable; and 2) augmenting the
Transformer decoder with a sequence of fine-grained latent variables. Then, the
proposed models are evaluated on three conversational datasets with both
automatic metric and human evaluation. The experimental results show that our
models improve standard Transformers and other baselines in terms of diversity,
semantic relevance, and human judgment.