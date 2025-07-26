---
layout: publication
title: 'Step-aware Preference Optimization: Aligning Preference With Denoising Performance
  At Each Step'
authors: Zhanhao Liang, Yuhui Yuan, Shuyang Gu, Bohan Chen, Tiankai Hang, Ji Li, Liang
  Zheng
conference: No Venue
year: 2024
bibkey: liang2024step
additional_links: [{name: Code, url: 'https://rockeycoss.github.io/spo.github.io/'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6662709f68009120affc7b77'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2406.04314'}]
tags: ["Efficiency", "Has Code", "Reinforcement Learning", "Training Techniques"]
short_authors: Liang et al.
---
Recently, Direct Preference Optimization (DPO) has extended its success from aligning large language models (LLMs) to aligning text-to-image diffusion models with human preferences. Unlike most existing DPO methods that assume all diffusion steps share a consistent preference order with the final generated images, we argue that this assumption neglects step-specific denoising performance and that preference labels should be tailored to each step's contribution. To address this limitation, we propose Step-aware Preference Optimization (SPO), a novel post-training approach that independently evaluates and adjusts the denoising performance at each step, using a step-aware preference model and a step-wise resampler to ensure accurate step-aware supervision. Specifically, at each denoising step, we sample a pool of images, find a suitable win-lose pair, and, most importantly, randomly select a single image from the pool to initialize the next denoising step. This step-wise resampler process ensures the next win-lose image pair comes from the same image, making the win-lose comparison independent of the previous step. To assess the preferences at each step, we train a separate step-aware preference model that can be applied to both noisy and clean images. Our experiments with Stable Diffusion v1.5 and SDXL demonstrate that SPO significantly outperforms the latest Diffusion-DPO in aligning generated images with complex, detailed prompts and enhancing aesthetics, while also achieving more than 20x times faster in training efficiency. Code and model: https://rockeycoss.github.io/spo.github.io/

https://huggingface.co/discussions/paper/6662709f68009120affc7b77