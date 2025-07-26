---
layout: publication
title: 'Upsample What Matters: Region-adaptive Latent Sampling For Accelerated Diffusion
  Transformers'
authors: Wongi Jeong, Kyungryeol Lee, Hoigi Seo, Se Young Chun
conference: No Venue
year: 2025
bibkey: jeong2025upsample
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.08422'}]
tags: ["Training Techniques"]
short_authors: Jeong et al.
---
Diffusion transformers have emerged as an alternative to U-net-based diffusion models for high-fidelity image and video generation, offering superior scalability. However, their heavy computation remains a major obstacle to real-world deployment. Existing acceleration methods primarily exploit the temporal dimension such as reusing cached features across diffusion timesteps. Here, we propose Region-Adaptive Latent Upsampling (RALU), a training-free framework that accelerates inference along spatial dimension. RALU performs mixed-resolution sampling across three stages: 1) low-resolution denoising latent diffusion to efficiently capture global semantic structure, 2) region-adaptive upsampling on specific regions prone to artifacts at full-resolution, and 3) all latent upsampling at full-resolution for detail refinement. To stabilize generations across resolution transitions, we leverage noise-timestep rescheduling to adapt the noise level across varying resolutions. Our method significantly reduces computation while preserving image quality by achieving up to 7.0times speed-up on FLUX and 3.0times on Stable Diffusion 3 with minimal degradation. Furthermore, RALU is complementary to existing temporal accelerations such as caching methods, thus can be seamlessly integrated to further reduce inference latency without compromising generation quality.

https://huggingface.co/discussions/paper/6880820200f4b5a05f2fbeb5