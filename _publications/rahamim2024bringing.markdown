---
layout: publication
title: 'Bringing Objects To Life: 4D Generation From 3D Objects'
authors: Ohad Rahamim, Ori Malca, Dvir Samuel, Gal Chechik
conference: No Venue
year: 2024
bibkey: rahamim2024bringing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.20422'}]
tags: ["Applications"]
short_authors: Rahamim et al.
---
Recent advancements in generative modeling now enable the creation of 4D content (moving 3D objects) controlled with text prompts. 4D generation has large potential in applications like virtual worlds, media, and gaming, but existing methods provide limited control over the appearance and geometry of generated content. In this work, we introduce a method for animating user-provided 3D objects by conditioning on textual prompts to guide 4D generation, enabling custom animations while maintaining the identity of the original object. We first convert a 3D mesh into a ``static" 4D Neural Radiance Field (NeRF) that preserves the visual attributes of the input object. Then, we animate the object using an Image-to-Video diffusion model driven by text. To improve motion realism, we introduce an incremental viewpoint selection protocol for sampling perspectives to promote lifelike movement and a masked Score Distillation Sampling (SDS) loss, which leverages attention maps to focus optimization on relevant regions. We evaluate our model in terms of temporal coherence, prompt adherence, and visual fidelity and find that our method outperforms baselines that are based on other approaches, achieving up to threefold improvements in identity preservation measured using LPIPS scores, and effectively balancing visual quality with dynamic content.

https://huggingface.co/discussions/paper/67738c513be2064a656e7ebd