---
layout: publication
title: 'Instant3d: Fast Text-to-3d With Sparse-view Generation And Large Reconstruction
  Model'
authors: Jiahao Li, Hao Tan, Kai Zhang, Zexiang Xu, Fujun Luan, Yinghao Xu, Yicong
  Hong, Kalyan Sunkavalli, Greg Shakhnarovich, Sai Bi
conference: No Venue
year: 2023
bibkey: li2023instant3d
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2311.06214'}]
tags: ["Efficiency", "Model Architecture", "Training Techniques"]
short_authors: Li et al.
---
Text-to-3D with diffusion models have achieved remarkable progress in recent years. However, existing methods either rely on score distillation-based optimization which suffer from slow inference, low diversity and Janus problems, or are feed-forward methods that generate low quality results due to the scarcity of 3D training data. In this paper, we propose Instant3D, a novel method that generates high-quality and diverse 3D assets from text prompts in a feed-forward manner. We adopt a two-stage paradigm, which first generates a sparse set of four structured and consistent views from text in one shot with a fine-tuned 2D text-to-image diffusion model, and then directly regresses the NeRF from the generated images with a novel transformer-based sparse-view reconstructor. Through extensive experiments, we demonstrate that our method can generate high-quality, diverse and Janus-free 3D assets within 20 seconds, which is two order of magnitude faster than previous optimization-based methods that can take 1 to 10 hours. Our project webpage: https://jiahao.ai/instant3d/.

https://huggingface.co/discussions/paper/65519d7b0774258908da06c3