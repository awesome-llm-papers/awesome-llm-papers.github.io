---
layout: publication
title: 'Videoanydoor: High-fidelity Video Object Insertion With Precise Motion Control'
authors: Yuanpeng Tu, Hao Luo, Xi Chen, Sihui Ji, Xiang Bai, Hengshuang Zhao
conference: No Venue
year: 2025
bibkey: tu2025videoanydoor
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.01427'}]
tags: ["Applications"]
short_authors: Tu et al.
---
Despite significant advancements in video generation, inserting a given object into videos remains a challenging task. The difficulty lies in preserving the appearance details of the reference object and accurately modeling coherent motions at the same time. In this paper, we propose VideoAnydoor, a zero-shot video object insertion framework with high-fidelity detail preservation and precise motion control. Starting from a text-to-video model, we utilize an ID extractor to inject the global identity and leverage a box sequence to control the overall motion. To preserve the detailed appearance and meanwhile support fine-grained motion control, we design a pixel warper. It takes the reference image with arbitrary key-points and the corresponding key-point trajectories as inputs. It warps the pixel details according to the trajectories and fuses the warped features with the diffusion U-Net, thus improving detail preservation and supporting users in manipulating the motion trajectories. In addition, we propose a training strategy involving both videos and static images with a reweight reconstruction loss to enhance insertion quality. VideoAnydoor demonstrates significant superiority over existing methods and naturally supports various downstream applications (e.g., talking head generation, video virtual try-on, multi-region editing) without task-specific fine-tuning.

https://huggingface.co/discussions/paper/6777523c1ab3b3341103325a