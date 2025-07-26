---
layout: publication
title: 'Dialogwae: Multimodal Response Generation With Conditional Wasserstein Auto-encoder'
authors: Xiaodong Gu, Kyunghyun Cho, Jung-woo Ha, Sunghun Kim
conference: Arxiv
year: 2018
bibkey: gu2018dialogwae
citations: 103
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.12352'}]
tags: ["Dialogue & Multi Turn"]
short_authors: Gu et al.
---
Variational autoencoders~(VAEs) have shown a promise in data-driven
conversation modeling. However, most VAE conversation models match the
approximate posterior distribution over the latent variables to a simple prior
such as standard normal distribution, thereby restricting the generated
responses to a relatively simple (e.g., unimodal) scope. In this paper, we
propose DialogWAE, a conditional Wasserstein autoencoder~(WAE) specially
designed for dialogue modeling. Unlike VAEs that impose a simple distribution
over the latent variables, DialogWAE models the distribution of data by
training a GAN within the latent variable space. Specifically, our model
samples from the prior and posterior distributions over the latent variables by
transforming context-dependent random noise using neural networks and minimizes
the Wasserstein distance between the two distributions. We further develop a
Gaussian mixture prior network to enrich the latent space. Experiments on two
popular datasets show that DialogWAE outperforms the state-of-the-art
approaches in generating more coherent, informative and diverse responses.