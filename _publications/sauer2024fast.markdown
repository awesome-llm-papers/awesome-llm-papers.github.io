---
layout: publication
title: Fast High-resolution Image Synthesis With Latent Adversarial Diffusion Distillation
authors: Axel Sauer, Frederic Boesel, Tim Dockhorn, Andreas Blattmann, Patrick Esser,
  Robin Rombach
conference: No Venue
year: 2024
bibkey: sauer2024fast
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2403.12015'}]
tags: ["Applications", "Efficiency", "Training Techniques"]
short_authors: Sauer et al.
---
Diffusion models are the main driver of progress in image and video synthesis, but suffer from slow inference speed. Distillation methods, like the recently introduced adversarial diffusion distillation (ADD) aim to shift the model from many-shot to single-step inference, albeit at the cost of expensive and difficult optimization due to its reliance on a fixed pretrained DINOv2 discriminator. We introduce Latent Adversarial Diffusion Distillation (LADD), a novel distillation approach overcoming the limitations of ADD. In contrast to pixel-based ADD, LADD utilizes generative features from pretrained latent diffusion models. This approach simplifies training and enhances performance, enabling high-resolution multi-aspect ratio image synthesis. We apply LADD to Stable Diffusion 3 (8B) to obtain SD3-Turbo, a fast model that matches the performance of state-of-the-art text-to-image generators using only four unguided sampling steps. Moreover, we systematically investigate its scaling behavior and demonstrate LADD's effectiveness in various applications such as image editing and inpainting.

https://huggingface.co/discussions/paper/65f90379d09e592f404b8656