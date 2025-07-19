---
layout: publication
title: Diffusion Meets Few-shot Class Incremental Learning
authors: Kim et al.
conference: 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: kim2025diffusion
citations: 310
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.23402'}]
tags: [Training Techniques, Distillation, Tools, CVPR, Ethics And Bias, Few Shot,
  Efficiency And Optimization, Reinforcement Learning, Merging]
---
Few-shot class-incremental learning (FSCIL) is challenging due to extremely
limited training data; while aiming to reduce catastrophic forgetting and learn
new information. We propose Diffusion-FSCIL, a novel approach that employs a
text-to-image diffusion model as a frozen backbone. Our conjecture is that
FSCIL can be tackled using a large generative model's capabilities benefiting
from 1) generation ability via large-scale pre-training; 2) multi-scale
representation; 3) representational flexibility through the text encoder. To
maximize the representation capability, we propose to extract multiple
complementary diffusion features to play roles as latent replay with slight
support from feature distillation for preventing generative biases. Our
framework realizes efficiency through 1) using a frozen backbone; 2) minimal
trainable components; 3) batch processing of multiple feature extractions.
Extensive experiments on CUB-200, miniImageNet, and CIFAR-100 show that
Diffusion-FSCIL surpasses state-of-the-art methods, preserving performance on
previously learned classes and adapting effectively to new ones.