---
layout: publication
title: 'Tech: Text-guided Reconstruction Of Lifelike Clothed Humans'
authors: Yangyi Huang, Hongwei Yi, Yuliang Xiu, Tingting Liao, Jiaxiang Tang, Deng
  Cai, Justus Thies
conference: No Venue
year: 2023
bibkey: huang2023tech
additional_links: [{name: Code, url: 'https://huangyangyi.github.io/tech'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/64ddc4ab78aef6e48918919a'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2308.08545'}]
tags: ["Has Code"]
short_authors: Huang et al.
---
Despite recent research advancements in reconstructing clothed humans from a single image, accurately restoring the "unseen regions" with high-level details remains an unsolved challenge that lacks attention. Existing methods often generate overly smooth back-side surfaces with a blurry texture. But how to effectively capture all visual attributes of an individual from a single image, which are sufficient to reconstruct unseen areas (e.g., the back view)? Motivated by the power of foundation models, TeCH reconstructs the 3D human by leveraging 1) descriptive text prompts (e.g., garments, colors, hairstyles) which are automatically generated via a garment parsing model and Visual Question Answering (VQA), 2) a personalized fine-tuned Text-to-Image diffusion model (T2I) which learns the "indescribable" appearance. To represent high-resolution 3D clothed humans at an affordable cost, we propose a hybrid 3D representation based on DMTet, which consists of an explicit body shape grid and an implicit distance field. Guided by the descriptive prompts + personalized T2I diffusion model, the geometry and texture of the 3D humans are optimized through multi-view Score Distillation Sampling (SDS) and reconstruction losses based on the original observation. TeCH produces high-fidelity 3D clothed humans with consistent & delicate texture, and detailed full-body geometry. Quantitative and qualitative experiments demonstrate that TeCH outperforms the state-of-the-art methods in terms of reconstruction accuracy and rendering quality. The code will be publicly available for research purposes at https://huangyangyi.github.io/tech

https://huggingface.co/discussions/paper/64ddc4ab78aef6e48918919a