---
layout: publication
title: Data-free Group-wise Fully Quantized Winograd Convolution Via Learnable Scales
authors: Pan et al.
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: pan2024data
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.19867'}]
tags: [RAG, Training Techniques, CVPR, Efficiency And Optimization, Quantization,
  Merging]
---
Despite the revolutionary breakthroughs of large-scale text-to-image
diffusion models for complex vision and downstream tasks, their extremely high
computational and storage costs limit their usability. Quantization of
diffusion models has been explored in recent works to reduce compute costs and
memory bandwidth usage. To further improve inference time, fast convolution
algorithms such as Winograd can be used for convolution layers, which account
for a significant portion of computations in diffusion models. However, the
significant quality loss of fully quantized Winograd using existing
coarser-grained post-training quantization methods, combined with the
complexity and cost of finetuning the Winograd transformation matrices for such
large models to recover quality, makes them unsuitable for large-scale
foundation models. Motivated by the presence of a large range of values in
them, we investigate the impact of finer-grained group-wise quantization in
quantizing diffusion models. While group-wise quantization can largely handle
the fully quantized Winograd convolution, it struggles to deal with the large
distribution imbalance in a sizable portion of the Winograd domain computation.
To reduce range differences in the Winograd domain, we propose finetuning only
the scale parameters of the Winograd transform matrices without using any
domain-specific training data. Because our method does not depend on any
training data, the generalization performance of quantized diffusion models is
safely guaranteed. For text-to-image generation task, the 8-bit fully-quantized
diffusion model with Winograd provides near-lossless quality (FID and CLIP
scores) in comparison to the full-precision model. For image classification,
our method outperforms the state-of-the-art Winograd PTQ method by 1.62% and
2.56% in top-1 ImageNet accuracy on ResNet18 and ResNet-34, respectively, with
Winograd F(6, 3).