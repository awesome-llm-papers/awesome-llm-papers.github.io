---
layout: publication
title: 'Fifo-diffusion: Generating Infinite Videos From Text Without Training'
authors: Jihwan Kim, Junoh Kang, Jinyoung Choi, Bohyung Han
conference: No Venue
year: 2024
bibkey: kim2024fifo
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2405.11473'}]
tags: ["Training Techniques"]
short_authors: Kim et al.
---
We propose a novel inference technique based on a pretrained diffusion model for text-conditional video generation. Our approach, called FIFO-Diffusion, is conceptually capable of generating infinitely long videos without training. This is achieved by iteratively performing diagonal denoising, which concurrently processes a series of consecutive frames with increasing noise levels in a queue; our method dequeues a fully denoised frame at the head while enqueuing a new random noise frame at the tail. However, diagonal denoising is a double-edged sword as the frames near the tail can take advantage of cleaner ones by forward reference but such a strategy induces the discrepancy between training and inference. Hence, we introduce latent partitioning to reduce the training-inference gap and lookahead denoising to leverage the benefit of forward referencing. We have demonstrated the promising results and effectiveness of the proposed methods on existing text-to-video generation baselines.

https://huggingface.co/discussions/paper/664c080a2f72dbb18fbcdbbe