---
layout: publication
title: Marrying Autoregressive Transformer And Diffusion With Multi-reference Autoregression
authors: Dingcheng Zhen, Qian Qiao, Tan Yu, Kangxi Wu, Ziwei Zhang, Siyuan Liu, Shunshun
  Yin, Ming Tao
conference: No Venue
year: 2025
bibkey: zhen2025marrying
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/684eb86b60b4a34dbe007a12'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.09482'}]
tags: ["Model Architecture"]
short_authors: Zhen et al.
---
We introduce TransDiff, the first image generation model that marries Autoregressive (AR) Transformer with diffusion models. In this joint modeling framework, TransDiff encodes labels and images into high-level semantic features and employs a diffusion model to estimate the distribution of image samples. On the ImageNet 256x256 benchmark, TransDiff significantly outperforms other image generation models based on standalone AR Transformer or diffusion models. Specifically, TransDiff achieves a Fr\'echet Inception Distance (FID) of 1.61 and an Inception Score (IS) of 293.4, and further provides x2 faster inference latency compared to state-of-the-art methods based on AR Transformer and x112 faster inference compared to diffusion-only models. Furthermore, building on the TransDiff model, we introduce a novel image generation paradigm called Multi-Reference Autoregression (MRAR), which performs autoregressive generation by predicting the next image. MRAR enables the model to reference multiple previously generated images, thereby facilitating the learning of more diverse representations and improving the quality of generated images in subsequent iterations. By applying MRAR, the performance of TransDiff is improved, with the FID reduced from 1.61 to 1.42. We expect TransDiff to open up a new frontier in the field of image generation.

https://huggingface.co/discussions/paper/684eb86b60b4a34dbe007a12