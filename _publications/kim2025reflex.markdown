---
layout: publication
title: 'Reflex: Text-guided Editing Of Real Images In Rectified Flow Via Mid-step
  Feature Extraction And Attention Adaptation'
authors: Kim et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: kim2025reflex
citations: 347
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2507.01496'}]
tags: [RAG, Training Techniques, Attention Mechanism, Prompting, CVPR, Evaluation,
  Transformer, Model Architecture, Multimodal Models, Datasets, Merging]
---
Rectified Flow text-to-image models surpass diffusion models in image quality and text alignment, but adapting ReFlow for real-image editing remains challenging. We propose a new real-image editing method for ReFlow by analyzing the intermediate representations of multimodal transformer blocks and identifying three key features. To extract these features from real images with sufficient structural preservation, we leverage mid-step latent, which is inverted only up to the mid-step. We then adapt attention during injection to improve editability and enhance alignment to the target text. Our method is training-free, requires no user-provided mask, and can be applied even without a source prompt. Extensive experiments on two benchmarks with nine baselines demonstrate its superior performance over prior methods, further validated by human evaluations confirming a strong user preference for our approach.