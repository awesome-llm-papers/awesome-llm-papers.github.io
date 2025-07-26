---
layout: publication
title: 'Instantid: Zero-shot Identity-preserving Generation In Seconds'
authors: Qixun Wang, Xu Bai, Haofan Wang, Zekui Qin, Anthony Chen
conference: No Venue
year: 2024
bibkey: wang2024instantid
additional_links: [{name: Code, url: 'https://github.com/InstantID/InstantID'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/65a76b963d3c83940823ec78'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2401.07519'}]
tags: ["Applications", "Efficiency"]
short_authors: Wang et al.
---
There has been significant progress in personalized image synthesis with methods such as Textual Inversion, DreamBooth, and LoRA. Yet, their real-world applicability is hindered by high storage demands, lengthy fine-tuning processes, and the need for multiple reference images. Conversely, existing ID embedding-based methods, while requiring only a single forward inference, face challenges: they either necessitate extensive fine-tuning across numerous model parameters, lack compatibility with community pre-trained models, or fail to maintain high face fidelity. Addressing these limitations, we introduce InstantID, a powerful diffusion model-based solution. Our plug-and-play module adeptly handles image personalization in various styles using just a single facial image, while ensuring high fidelity. To achieve this, we design a novel IdentityNet by imposing strong semantic and weak spatial conditions, integrating facial and landmark images with textual prompts to steer the image generation. InstantID demonstrates exceptional performance and efficiency, proving highly beneficial in real-world applications where identity preservation is paramount. Moreover, our work seamlessly integrates with popular pre-trained text-to-image diffusion models like SD1.5 and SDXL, serving as an adaptable plugin. Our codes and pre-trained checkpoints will be available at https://github.com/InstantID/InstantID.

https://huggingface.co/discussions/paper/65a76b963d3c83940823ec78