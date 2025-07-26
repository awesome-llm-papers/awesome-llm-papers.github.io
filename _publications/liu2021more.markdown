---
layout: publication
title: More Control For Free! Image Synthesis With Semantic Diffusion Guidance
authors: Xihui Liu, Dong Huk Park, Samaneh Azadi, Gong Zhang, Arman Chopikyan, Yuxiao
  Hu, Humphrey Shi, Anna Rohrbach, Trevor Darrell
conference: 2023 IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)
year: 2023
bibkey: liu2021more
citations: 115
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.05744'}]
tags: ["Applications", "Tools"]
short_authors: Liu et al.
---
Controllable image synthesis models allow creation of diverse images based on
text instructions or guidance from a reference image. Recently, denoising
diffusion probabilistic models have been shown to generate more realistic
imagery than prior methods, and have been successfully demonstrated in
unconditional and class-conditional settings. We investigate fine-grained,
continuous control of this model class, and introduce a novel unified framework
for semantic diffusion guidance, which allows either language or image
guidance, or both. Guidance is injected into a pretrained unconditional
diffusion model using the gradient of image-text or image matching scores,
without re-training the diffusion model. We explore CLIP-based language
guidance as well as both content and style-based image guidance in a unified
framework. Our text-guided synthesis approach can be applied to datasets
without associated text annotations. We conduct experiments on FFHQ and LSUN
datasets, and show results on fine-grained text-guided image synthesis,
synthesis of images related to a style or content reference image, and examples
with both textual and image guidance.