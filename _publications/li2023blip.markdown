---
layout: publication
title: 'Blip-diffusion: Pre-trained Subject Representation For Controllable Text-to-image
  Generation And Editing'
authors: Dongxu Li, Junnan Li, Steven C. H. Hoi
conference: Arxiv
year: 2023
bibkey: li2023blip
citations: 630
additional_links: [{name: Code, url: 'https://github.com/salesforce/LAVIS/tree/main/projects/blip-diffusion'},
  {name: Code, url: 'https://dxli94.github.io/BLIP-Diffusion-website/'}, {name: Paper,
    url: 'https://arxiv.org/abs/2305.14720'}]
tags: ["Applications", "Fine-Tuning"]
short_authors: Dongxu Li, Junnan Li, Steven C. H. Hoi
---
Subject-driven text-to-image generation models create novel renditions of an
input subject based on text prompts. Existing models suffer from lengthy
fine-tuning and difficulties preserving the subject fidelity. To overcome these
limitations, we introduce BLIP-Diffusion, a new subject-driven image generation
model that supports multimodal control which consumes inputs of subject images
and text prompts. Unlike other subject-driven generation models, BLIP-Diffusion
introduces a new multimodal encoder which is pre-trained to provide subject
representation. We first pre-train the multimodal encoder following BLIP-2 to
produce visual representation aligned with the text. Then we design a subject
representation learning task which enables a diffusion model to leverage such
visual representation and generates new subject renditions. Compared with
previous methods such as DreamBooth, our model enables zero-shot subject-driven
generation, and efficient fine-tuning for customized subject with up to 20x
speedup. We also demonstrate that BLIP-Diffusion can be flexibly combined with
existing techniques such as ControlNet and prompt-to-prompt to enable novel
subject-driven generation and editing applications. Code and models will be
released at
https://github.com/salesforce/LAVIS/tree/main/projects/blip-diffusion. Project
page at https://dxli94.github.io/BLIP-Diffusion-website/.