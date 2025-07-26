---
layout: publication
title: 'T-lora: Single Image Diffusion Model Customization Without Overfitting'
authors: Vera Soboleva, Aibek Alanov, Andrey Kuznetsov, Konstantin Sobolev
conference: No Venue
year: 2025
bibkey: soboleva2025t
additional_links: [{name: Code, url: 'https://github.com/ControlGenAI/T-LoRA'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/6870b8b5c8391850d60978e4'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2507.05964'}]
tags: ["Fine-Tuning", "Has Code", "Tools", "Training Techniques"]
short_authors: Soboleva et al.
---
While diffusion model fine-tuning offers a powerful approach for customizing pre-trained models to generate specific objects, it frequently suffers from overfitting when training samples are limited, compromising both generalization capability and output diversity. This paper tackles the challenging yet most impactful task of adapting a diffusion model using just a single concept image, as single-image customization holds the greatest practical potential. We introduce T-LoRA, a Timestep-Dependent Low-Rank Adaptation framework specifically designed for diffusion model personalization. In our work we show that higher diffusion timesteps are more prone to overfitting than lower ones, necessitating a timestep-sensitive fine-tuning strategy. T-LoRA incorporates two key innovations: (1) a dynamic fine-tuning strategy that adjusts rank-constrained updates based on diffusion timesteps, and (2) a weight parametrization technique that ensures independence between adapter components through orthogonal initialization. Extensive experiments show that T-LoRA and its individual components outperform standard LoRA and other diffusion model personalization techniques. They achieve a superior balance between concept fidelity and text alignment, highlighting the potential of T-LoRA in data-limited and resource-constrained scenarios. Code is available at https://github.com/ControlGenAI/T-LoRA.

https://huggingface.co/discussions/paper/6870b8b5c8391850d60978e4