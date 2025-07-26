---
layout: publication
title: 'Mvdream: Multi-view Diffusion For 3D Generation'
authors: Yichun Shi, Peng Wang, Jianglong Ye, Mai Long, Kejie Li, Xiao Yang
conference: No Venue
year: 2023
bibkey: shi2023mvdream
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2308.16512'}]
tags: ["Datasets", "Efficiency", "Prompting"]
short_authors: Shi et al.
---
We propose MVDream, a multi-view diffusion model that is able to generate geometrically consistent multi-view images from a given text prompt. By leveraging image diffusion models pre-trained on large-scale web datasets and a multi-view dataset rendered from 3D assets, the resulting multi-view diffusion model can achieve both the generalizability of 2D diffusion and the consistency of 3D data. Such a model can thus be applied as a multi-view prior for 3D generation via Score Distillation Sampling, where it greatly improves the stability of existing 2D-lifting methods by solving the 3D consistency problem. Finally, we show that the multi-view diffusion model can also be fine-tuned under a few shot setting for personalized 3D generation, i.e. DreamBooth3D application, where the consistency can be maintained after learning the subject identity.

https://huggingface.co/discussions/paper/64f19b8599cfca31353b5ee0