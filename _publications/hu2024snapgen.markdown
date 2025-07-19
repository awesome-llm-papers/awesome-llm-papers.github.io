---
layout: publication
title: 'Snapgen: Taming High-resolution Text-to-image Models For Mobile Devices With
  Efficient Architectures And Training'
authors: Hu et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: hu2024snapgen
citations: 1370
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.09619'}]
tags: [Training Techniques, Distillation, Tools, CVPR, Evaluation, Model Architecture,
  Efficiency And Optimization, Security, Datasets, Merging]
---
Existing text-to-image (T2I) diffusion models face several limitations,
including large model sizes, slow runtime, and low-quality generation on mobile
devices. This paper aims to address all of these challenges by developing an
extremely small and fast T2I model that generates high-resolution and
high-quality images on mobile platforms. We propose several techniques to
achieve this goal. First, we systematically examine the design choices of the
network architecture to reduce model parameters and latency, while ensuring
high-quality generation. Second, to further improve generation quality, we
employ cross-architecture knowledge distillation from a much larger model,
using a multi-level approach to guide the training of our model from scratch.
Third, we enable a few-step generation by integrating adversarial guidance with
knowledge distillation. For the first time, our model SnapGen, demonstrates the
generation of 1024x1024 px images on a mobile device around 1.4 seconds. On
ImageNet-1K, our model, with only 372M parameters, achieves an FID of 2.06 for
256x256 px generation. On T2I benchmarks (i.e., GenEval and DPG-Bench), our
model with merely 379M parameters, surpasses large-scale models with billions
of parameters at a significantly smaller size (e.g., 7x smaller than SDXL, 14x
smaller than IF-XL).