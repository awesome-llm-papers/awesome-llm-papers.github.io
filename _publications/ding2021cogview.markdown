---
layout: publication
title: 'Cogview: Mastering Text-to-image Generation Via Transformers'
authors: Ming Ding, Zhuoyi Yang, Wenyi Hong, Wendi Zheng, Chang Zhou, da Yin, Junyang
  Lin, Xu Zou, Zhou Shao, Hongxia Yang, Jie Tang
conference: Arxiv
year: 2021
bibkey: ding2021cogview
citations: 268
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.13290'}]
tags: ["Model Architecture"]
short_authors: Ding et al.
---
Text-to-Image generation in the general domain has long been an open problem,
which requires both a powerful generative model and cross-modal understanding.
We propose CogView, a 4-billion-parameter Transformer with VQ-VAE tokenizer to
advance this problem. We also demonstrate the finetuning strategies for various
downstream tasks, e.g. style learning, super-resolution, text-image ranking and
fashion design, and methods to stabilize pretraining, e.g. eliminating NaN
losses. CogView achieves the state-of-the-art FID on the blurred MS COCO
dataset, outperforming previous GAN-based models and a recent similar work
DALL-E.