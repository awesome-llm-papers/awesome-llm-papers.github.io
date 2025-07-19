---
layout: publication
title: Synthetic Data From Diffusion Models Improves Imagenet Classification
authors: Azizi et al.
conference: Arxiv
year: 2023
bibkey: azizi2023synthetic
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.08466'}]
tags: [Training Techniques, Prompting, Transformer, Model Architecture, Merging]
---
Deep generative models are becoming increasingly powerful, now generating
diverse high fidelity photo-realistic samples given text prompts. Have they
reached the point where models of natural images can be used for generative
data augmentation, helping to improve challenging discriminative tasks? We show
that large-scale text-to image diffusion models can be fine-tuned to produce
class conditional models with SOTA FID (1.76 at 256x256 resolution) and
Inception Score (239 at 256x256). The model also yields a new SOTA in
Classification Accuracy Scores (64.96 for 256x256 generative samples, improving
to 69.24 for 1024x1024 samples). Augmenting the ImageNet training set with
samples from the resulting models yields significant improvements in ImageNet
classification accuracy over strong ResNet and Vision Transformer baselines.