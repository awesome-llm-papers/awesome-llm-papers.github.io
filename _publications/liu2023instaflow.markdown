---
layout: publication
title: 'Instaflow: One Step Is Enough For High-quality Diffusion-based Text-to-image
  Generation'
authors: Xingchao Liu, Xiwen Zhang, Jianzhu Ma, Jian Peng, Qiang Liu
conference: No Venue
year: 2023
bibkey: liu2023instaflow
additional_links: [{name: Code, url: 'https://github.com/gnobitab/InstaFlow'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2309.06380'}]
tags: ["Datasets", "Efficiency", "Has Code", "Training Techniques"]
short_authors: Liu et al.
---
Diffusion models have revolutionized text-to-image generation with its exceptional quality and creativity. However, its multi-step sampling process is known to be slow, often requiring tens of inference steps to obtain satisfactory results. Previous attempts to improve its sampling speed and reduce computational costs through distillation have been unsuccessful in achieving a functional one-step model. In this paper, we explore a recent method called Rectified Flow, which, thus far, has only been applied to small datasets. The core of Rectified Flow lies in its reflow procedure, which straightens the trajectories of probability flows, refines the coupling between noises and images, and facilitates the distillation process with student models. We propose a novel text-conditioned pipeline to turn Stable Diffusion (SD) into an ultra-fast one-step model, in which we find reflow plays a critical role in improving the assignment between noise and images. Leveraging our new pipeline, we create, to the best of our knowledge, the first one-step diffusion-based text-to-image generator with SD-level image quality, achieving an FID (Frechet Inception Distance) of 23.3 on MS COCO 2017-5k, surpassing the previous state-of-the-art technique, progressive distillation, by a significant margin (37.2 rightarrow 23.3 in FID). By utilizing an expanded network with 1.7B parameters, we further improve the FID to 22.4. We call our one-step models InstaFlow. On MS COCO 2014-30k, InstaFlow yields an FID of 13.1 in just 0.09 second, the best in leq 0.1 second regime, outperforming the recent StyleGAN-T (13.9 in 0.1 second). Notably, the training of InstaFlow only costs 199 A100 GPU days. Project page:~https://github.com/gnobitab/InstaFlow.

https://huggingface.co/discussions/paper/65011cce70b6b05c5af0c51d