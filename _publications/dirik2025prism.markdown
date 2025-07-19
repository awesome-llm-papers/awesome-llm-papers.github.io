---
layout: publication
title: 'PRISM: A Unified Framework For Photorealistic Reconstruction And Intrinsic
  Scene Modeling'
authors: Dirik et al.
conference: Proceedings of IEEE Computer Society Conference on Computer Vision and
  Pattern Recognition
year: 2025
bibkey: dirik2025prism
citations: 249
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.14219'}]
tags: [Training Techniques, Prompting, Tools, CVPR, Reinforcement Learning, Fine Tuning,
  Merging]
---
We present PRISM, a unified framework that enables multiple image generation and editing tasks in a single foundational model. Starting from a pre-trained text-to-image diffusion model, PRISM proposes an effective fine-tuning strategy to produce RGB images along with intrinsic maps (referred to as X layers) simultaneously. Unlike previous approaches, which infer intrinsic properties individually or require separate models for decomposition and conditional generation, PRISM maintains consistency across modalities by generating all intrinsic layers jointly. It supports diverse tasks, including text-to-RGBX generation, RGB-to-X decomposition, and X-to-RGBX conditional generation. Additionally, PRISM enables both global and local image editing through conditioning on selected intrinsic layers and text prompts. Extensive experiments demonstrate the competitive performance of PRISM both for intrinsic image decomposition and conditional image generation while preserving the base model's text-to-image generation capability.