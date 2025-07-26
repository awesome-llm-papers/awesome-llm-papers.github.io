---
layout: publication
title: Language Generation With Recurrent Generative Adversarial Networks Without
  Pre-training
authors: Ofir Press, Amir Bar, Ben Bogin, Jonathan Berant, Lior Wolf
conference: Arxiv
year: 2017
bibkey: press2017language
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1706.01399'}]
tags: ["Security", "Training Techniques"]
short_authors: Press et al.
---
Generative Adversarial Networks (GANs) have shown great promise recently in
image generation. Training GANs for language generation has proven to be more
difficult, because of the non-differentiable nature of generating text with
recurrent neural networks. Consequently, past work has either resorted to
pre-training with maximum-likelihood or used convolutional networks for
generation. In this work, we show that recurrent neural networks can be trained
to generate text with GANs from scratch using curriculum learning, by slowly
teaching the model to generate sequences of increasing and variable length. We
empirically show that our approach vastly improves the quality of generated
sequences compared to a convolutional baseline.