---
layout: publication
title: 'Dragondiffusion: Enabling Drag-style Manipulation On Diffusion Models'
authors: Chong Mou, Xintao Wang, Jiechong Song, Ying Shan, Jian Zhang
conference: No Venue
year: 2023
bibkey: mou2023dragondiffusion
additional_links: [{name: Code, url: 'https://github.com/MC-E/DragonDiffusion'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/64a641230c2ce52c64ee6b8f'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2307.02421'}]
tags: ["Has Code"]
short_authors: Mou et al.
---
Despite the ability of existing large-scale text-to-image (T2I) models to generate high-quality images from detailed textual descriptions, they often lack the ability to precisely edit the generated or real images. In this paper, we propose a novel image editing method, DragonDiffusion, enabling Drag-style manipulation on Diffusion models. Specifically, we construct classifier guidance based on the strong correspondence of intermediate features in the diffusion model. It can transform the editing signals into gradients via feature correspondence loss to modify the intermediate representation of the diffusion model. Based on this guidance strategy, we also build a multi-scale guidance to consider both semantic and geometric alignment. Moreover, a cross-branch self-attention is added to maintain the consistency between the original image and the editing result. Our method, through an efficient design, achieves various editing modes for the generated or real images, such as object moving, object resizing, object appearance replacement, and content dragging. It is worth noting that all editing and content preservation signals come from the image itself, and the model does not require fine-tuning or additional modules. Our source code will be available at https://github.com/MC-E/DragonDiffusion.

https://huggingface.co/discussions/paper/64a641230c2ce52c64ee6b8f