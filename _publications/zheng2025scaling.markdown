---
layout: publication
title: "Scaling Diffusion Transformers Efficiently Via \u039Cp"
authors: Chenyu Zheng, Xinyu Zhang, Rongzhen Wang, Wei Huang, Zhi Tian, Weilin Huang,
  Jun Zhu, Chongxuan Li
conference: No Venue
year: 2025
bibkey: zheng2025scaling
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.15270'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Zheng et al.
---
Diffusion Transformers have emerged as the foundation for vision generative models, but their scalability is limited by the high cost of hyperparameter (HP) tuning at large scales. Recently, Maximal Update Parametrization (muP) was proposed for vanilla Transformers, which enables stable HP transfer from small to large language models, and dramatically reduces tuning costs. However, it remains unclear whether muP of vanilla Transformers extends to diffusion Transformers, which differ architecturally and objectively. In this work, we generalize standard muP to diffusion Transformers and validate its effectiveness through large-scale experiments. First, we rigorously prove that muP of mainstream diffusion Transformers, including DiT, U-ViT, PixArt-alpha, and MMDiT, aligns with that of the vanilla Transformer, enabling the direct application of existing muP methodologies. Leveraging this result, we systematically demonstrate that DiT-muP enjoys robust HP transferability. Notably, DiT-XL-2-muP with transferred learning rate achieves 2.9 times faster convergence than the original DiT-XL-2. Finally, we validate the effectiveness of muP on text-to-image generation by scaling PixArt-alpha from 0.04B to 0.61B and MMDiT from 0.18B to 18B. In both cases, models under muP outperform their respective baselines while requiring small tuning cost, only 5.5% of one training run for PixArt-alpha and 3% of consumption by human experts for MMDiT-18B. These results establish muP as a principled and efficient framework for scaling diffusion Transformers.

https://huggingface.co/discussions/paper/682e907b24b2bb08885b952c