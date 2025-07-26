---
layout: publication
title: Neural Network Diffusion
authors: Kai Wang, Zhaopan Xu, Yukun Zhou, Zelin Zang, Trevor Darrell, Zhuang Liu,
  Yang You
conference: No Venue
year: 2024
bibkey: wang2024neural
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65d565d1aa212698b489e0ad'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2402.13144'}]
tags: ["Datasets"]
short_authors: Wang et al.
---
Diffusion models have achieved remarkable success in image and video generation. In this work, we demonstrate that diffusion models can also generate high-performing neural network parameters. Our approach is simple, utilizing an autoencoder and a standard latent diffusion model. The autoencoder extracts latent representations of a subset of the trained network parameters. A diffusion model is then trained to synthesize these latent parameter representations from random noise. It then generates new representations that are passed through the autoencoder's decoder, whose outputs are ready to use as new subsets of network parameters. Across various architectures and datasets, our diffusion process consistently generates models of comparable or improved performance over trained networks, with minimal additional cost. Notably, we empirically find that the generated models perform differently with the trained networks. Our results encourage more exploration on the versatile use of diffusion models.

https://huggingface.co/discussions/paper/65d565d1aa212698b489e0ad