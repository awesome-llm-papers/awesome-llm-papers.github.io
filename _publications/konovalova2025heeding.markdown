---
layout: publication
title: 'Heeding The Inner Voice: Aligning Controlnet Training Via Intermediate Features
  Feedback'
authors: Nina Konovalova, Maxim Nikolaev, Andrey Kuznetsov, Aibek Alanov
conference: No Venue
year: 2025
bibkey: konovalova2025heeding
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.02321'}]
tags: ["Training Techniques"]
short_authors: Konovalova et al.
---
Despite significant progress in text-to-image diffusion models, achieving precise spatial control over generated outputs remains challenging. ControlNet addresses this by introducing an auxiliary conditioning module, while ControlNet++ further refines alignment through a cycle consistency loss applied only to the final denoising steps. However, this approach neglects intermediate generation stages, limiting its effectiveness. We propose InnerControl, a training strategy that enforces spatial consistency across all diffusion steps. Our method trains lightweight convolutional probes to reconstruct input control signals (e.g., edges, depth) from intermediate UNet features at every denoising step. These probes efficiently extract signals even from highly noisy latents, enabling pseudo ground truth controls for training. By minimizing the discrepancy between predicted and target conditions throughout the entire diffusion process, our alignment loss improves both control fidelity and generation quality. Combined with established techniques like ControlNet++, InnerControl achieves state-of-the-art performance across diverse conditioning methods (e.g., edges, depth).

https://huggingface.co/discussions/paper/68679bf2213f123a1f88b8c1