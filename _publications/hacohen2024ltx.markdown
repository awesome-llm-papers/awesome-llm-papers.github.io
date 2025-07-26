---
layout: publication
title: 'Ltx-video: Realtime Video Latent Diffusion'
authors: Yoav Hacohen, Nisan Chiprut, Benny Brazowski, Daniel Shalem, Dudu Moshe,
  Eitan Richardson, Eran Levin, Guy Shiran, Nir Zabari, Ori Gordon, Poriya Panet,
  Sapir Weissbuch, Victor Kulikov, Yaki Bitterman, Zeev Melumian, Ofir Bibi
conference: No Venue
year: 2024
bibkey: hacohen2024ltx
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6777ef06cbb36f508a37ab84'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2501.00103'}]
tags: ["Applications", "Efficiency", "Model Architecture"]
short_authors: Hacohen et al.
---
We introduce LTX-Video, a transformer-based latent diffusion model that adopts a holistic approach to video generation by seamlessly integrating the responsibilities of the Video-VAE and the denoising transformer. Unlike existing methods, which treat these components as independent, LTX-Video aims to optimize their interaction for improved efficiency and quality. At its core is a carefully designed Video-VAE that achieves a high compression ratio of 1:192, with spatiotemporal downscaling of 32 x 32 x 8 pixels per token, enabled by relocating the patchifying operation from the transformer's input to the VAE's input. Operating in this highly compressed latent space enables the transformer to efficiently perform full spatiotemporal self-attention, which is essential for generating high-resolution videos with temporal consistency. However, the high compression inherently limits the representation of fine details. To address this, our VAE decoder is tasked with both latent-to-pixel conversion and the final denoising step, producing the clean result directly in pixel space. This approach preserves the ability to generate fine details without incurring the runtime cost of a separate upsampling module. Our model supports diverse use cases, including text-to-video and image-to-video generation, with both capabilities trained simultaneously. It achieves faster-than-real-time generation, producing 5 seconds of 24 fps video at 768x512 resolution in just 2 seconds on an Nvidia H100 GPU, outperforming all existing models of similar scale. The source code and pre-trained models are publicly available, setting a new benchmark for accessible and scalable video generation.

https://huggingface.co/discussions/paper/6777ef06cbb36f508a37ab84