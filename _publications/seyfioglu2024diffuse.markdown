---
layout: publication
title: 'Diffuse To Choose: Enriching Image Conditioned Inpainting In Latent Diffusion
  Models For Virtual Try-all'
authors: Mehmet Saygin Seyfioglu, Karim Bouyarmane, Suren Kumar, Amir Tavanaei, Ismail
  B. Tutar
conference: No Venue
year: 2024
bibkey: seyfioglu2024diffuse
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2401.13795'}]
tags: ["Applications", "Datasets", "Few-Shot"]
short_authors: Seyfioglu et al.
---
As online shopping is growing, the ability for buyers to virtually visualize products in their settings-a phenomenon we define as "Virtual Try-All"-has become crucial. Recent diffusion models inherently contain a world model, rendering them suitable for this task within an inpainting context. However, traditional image-conditioned diffusion models often fail to capture the fine-grained details of products. In contrast, personalization-driven models such as DreamPaint are good at preserving the item's details but they are not optimized for real-time applications. We present "Diffuse to Choose," a novel diffusion-based image-conditioned inpainting model that efficiently balances fast inference with the retention of high-fidelity details in a given reference item while ensuring accurate semantic manipulations in the given scene content. Our approach is based on incorporating fine-grained features from the reference image directly into the latent feature maps of the main diffusion model, alongside with a perceptual loss to further preserve the reference item's details. We conduct extensive testing on both in-house and publicly available datasets, and show that Diffuse to Choose is superior to existing zero-shot diffusion inpainting methods as well as few-shot diffusion personalization algorithms like DreamPaint.

https://huggingface.co/discussions/paper/65b334dcda72b2526d3f9262