---
layout: publication
title: Exploring Vision Transformers As Diffusion Learners
authors: Cao et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2022
bibkey: cao2022exploring
citations: 118
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.13771'}]
tags: [Training Techniques, Attention Mechanism, Transformer, Model Architecture,
  AAAI, Merging]
---
Score-based diffusion models have captured widespread attention and funded
fast progress of recent vision generative tasks. In this paper, we focus on
diffusion model backbone which has been much neglected before. We
systematically explore vision Transformers as diffusion learners for various
generative tasks. With our improvements the performance of vanilla ViT-based
backbone (IU-ViT) is boosted to be on par with traditional U-Net-based methods.
We further provide a hypothesis on the implication of disentangling the
generative backbone as an encoder-decoder structure and show proof-of-concept
experiments verifying the effectiveness of a stronger encoder for generative
tasks with ASymmetriC ENcoder Decoder (ASCEND). Our improvements achieve
competitive results on CIFAR-10, CelebA, LSUN, CUB Bird and large-resolution
text-to-image tasks. To the best of our knowledge, we are the first to
successfully train a single diffusion model on text-to-image task beyond 64x64
resolution. We hope this will motivate people to rethink the modeling choices
and the training pipelines for diffusion-based generative models.