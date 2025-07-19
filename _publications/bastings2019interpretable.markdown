---
layout: publication
title: Interpretable Neural Predictions With Differentiable Binary Variables
authors: Bastings Jasmijn, Aziz Wilker, Titov Ivan
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: bastings2019interpretable
citations: 197
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.08160'}]
tags: [Model Architecture, Interpretability And Explainability, Training Techniques,
  ACL, Transformer, Attention Mechanism, Alt]
---
The success of neural networks comes hand in hand with a desire for more
interpretability. We focus on text classifiers and make them more interpretable
by having them provide a justification, a rationale, for their predictions. We
approach this problem by jointly training two neural network models: a latent
model that selects a rationale (i.e. a short and informative part of the input
text), and a classifier that learns from the words in the rationale alone.
Previous work proposed to assign binary latent masks to input positions and to
promote short selections via sparsity-inducing penalties such as L0
regularisation. We propose a latent model that mixes discrete and continuous
behaviour allowing at the same time for binary selections and gradient-based
training without REINFORCE. In our formulation, we can tractably compute the
expected value of penalties such as L0, which allows us to directly optimise
the model towards a pre-specified text selection rate. We show that our
approach is competitive with previous work on rationale extraction, and explore
further uses in attention mechanisms.