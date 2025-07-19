---
layout: publication
title: 'Diffusionclip: Text-guided Diffusion Models For Robust Image Manipulation'
authors: Kim Gwanghyun, Kwon Taesung, Ye Jong Chul
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2021
bibkey: kim2021diffusionclip
citations: 306
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.02711'}]
tags: [Training Techniques, Alt, Prompting, CVPR, Evaluation, Applications, Datasets,
  Merging]
---
Recently, GAN inversion methods combined with Contrastive Language-Image
Pretraining (CLIP) enables zero-shot image manipulation guided by text prompts.
However, their applications to diverse real images are still difficult due to
the limited GAN inversion capability. Specifically, these approaches often have
difficulties in reconstructing images with novel poses, views, and highly
variable contents compared to the training data, altering object identity, or
producing unwanted image artifacts. To mitigate these problems and enable
faithful manipulation of real images, we propose a novel method, dubbed
DiffusionCLIP, that performs text-driven image manipulation using diffusion
models. Based on full inversion capability and high-quality image generation
power of recent diffusion models, our method performs zero-shot image
manipulation successfully even between unseen domains and takes another step
towards general application by manipulating images from a widely varying
ImageNet dataset. Furthermore, we propose a novel noise combination method that
allows straightforward multi-attribute manipulation. Extensive experiments and
human evaluation confirmed robust and superior manipulation performance of our
methods compared to the existing baselines. Code is available at
https://github.com/gwang-kim/DiffusionCLIP.git.