---
layout: publication
title: 'Storydiffusion: Consistent Self-attention For Long-range Image And Video Generation'
authors: Yupeng Zhou, Daquan Zhou, Ming-ming Cheng, Jiashi Feng, Qibin Hou
conference: No Venue
year: 2024
bibkey: zhou2024storydiffusion
additional_links: [{name: Code, url: 'https://github.com/HVision-NKU/StoryDiffusion'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/663443b32adb91d8d9fa2c32'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2405.01434'}]
tags: ["Has Code", "Tools"]
short_authors: Zhou et al.
---
For recent diffusion-based generative models, maintaining consistent content across a series of generated images, especially those containing subjects and complex details, presents a significant challenge. In this paper, we propose a new way of self-attention calculation, termed Consistent Self-Attention, that significantly boosts the consistency between the generated images and augments prevalent pretrained diffusion-based text-to-image models in a zero-shot manner. To extend our method to long-range video generation, we further introduce a novel semantic space temporal motion prediction module, named Semantic Motion Predictor. It is trained to estimate the motion conditions between two provided images in the semantic spaces. This module converts the generated sequence of images into videos with smooth transitions and consistent subjects that are significantly more stable than the modules based on latent spaces only, especially in the context of long video generation. By merging these two novel components, our framework, referred to as StoryDiffusion, can describe a text-based story with consistent images or videos encompassing a rich variety of contents. The proposed StoryDiffusion encompasses pioneering explorations in visual story generation with the presentation of images and videos, which we hope could inspire more research from the aspect of architectural modifications. Our code is made publicly available at https://github.com/HVision-NKU/StoryDiffusion.

https://huggingface.co/discussions/paper/663443b32adb91d8d9fa2c32