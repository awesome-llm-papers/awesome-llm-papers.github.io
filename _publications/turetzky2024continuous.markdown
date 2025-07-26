---
layout: publication
title: Continuous Speech Synthesis Using Per-token Latent Diffusion
authors: Arnon Turetzky, Nimrod Shabtay, Slava Shechtman, Hagai Aronowitz, David Haws,
  Ron Hoory, Avihu Dekel
conference: No Venue
year: 2024
bibkey: turetzky2024continuous
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2410.16048'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Turetzky et al.
---
The success of autoregressive transformer models with discrete tokens has inspired quantization-based approaches for continuous modalities, though these often limit reconstruction quality. We therefore introduce SALAD, a per-token latent diffusion model for zero-shot text-to-speech, that operates on continuous representations. SALAD builds upon the recently proposed expressive diffusion head for image generation, and extends it to generate variable-length outputs. Our approach utilizes semantic tokens for providing contextual information and determining the stopping condition. We suggest three continuous variants for our method, extending popular discrete speech synthesis techniques. Additionally, we implement discrete baselines for each variant and conduct a comparative analysis of discrete versus continuous speech modeling techniques. Our results demonstrate that both continuous and discrete approaches are highly competent, and that SALAD achieves a superior intelligibility score while obtaining speech quality and speaker similarity on par with the ground-truth audio.

https://huggingface.co/discussions/paper/671753f49feb1b7d3a5f1124