---
layout: publication
title: Deconvolutional Latent-variable Model For Text Sequence Matching
authors: Shen et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2017
bibkey: shen2017deconvolutional
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1709.07109'}]
tags: [Model Architecture, Efficiency And Optimization, AAAI, Training Techniques]
---
A latent-variable model is introduced for text matching, inferring sentence
representations by jointly optimizing generative and discriminative objectives.
To alleviate typical optimization challenges in latent-variable models for
text, we employ deconvolutional networks as the sequence decoder (generator),
providing learned latent codes with more semantic information and better
generalization. Our model, trained in an unsupervised manner, yields stronger
empirical predictive performance than a decoder based on Long Short-Term Memory
(LSTM), with less parameters and considerably faster training. Further, we
apply it to text sequence-matching problems. The proposed model significantly
outperforms several strong sentence-encoding baselines, especially in the
semi-supervised setting.