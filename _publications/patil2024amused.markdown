---
layout: publication
title: 'Amused: An Open MUSE Reproduction'
authors: Suraj Patil, William Berman, Robin Rombach, Patrick von Platen
conference: No Venue
year: 2024
bibkey: patil2024amused
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65961d6312c3ee130fac1e32'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2401.01808'}]
tags: ["Training Techniques"]
short_authors: Patil et al.
---
We present aMUSEd, an open-source, lightweight masked image model (MIM) for text-to-image generation based on MUSE. With 10 percent of MUSE's parameters, aMUSEd is focused on fast image generation. We believe MIM is under-explored compared to latent diffusion, the prevailing approach for text-to-image generation. Compared to latent diffusion, MIM requires fewer inference steps and is more interpretable. Additionally, MIM can be fine-tuned to learn additional styles with only a single image. We hope to encourage further exploration of MIM by demonstrating its effectiveness on large-scale text-to-image generation and releasing reproducible training code. We also release checkpoints for two models which directly produce images at 256x256 and 512x512 resolutions.

https://huggingface.co/discussions/paper/65961d6312c3ee130fac1e32