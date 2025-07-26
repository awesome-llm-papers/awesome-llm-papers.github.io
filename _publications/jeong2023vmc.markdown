---
layout: publication
title: 'VMC: Video Motion Customization Using Temporal Attention Adaption For Text-to-video
  Diffusion Models'
authors: Hyeonho Jeong, Geon Yeong Park, Jong Chul Ye
conference: No Venue
year: 2023
bibkey: jeong2023vmc
additional_links: [{name: Code, url: 'https://video-motion-customization.github.io'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/656e90d6e9d3e5f3f7bac053'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2312.00845'}]
tags: ["Efficiency", "Has Code", "Tools"]
short_authors: Hyeonho Jeong, Geon Yeong Park, Jong Chul Ye
---
Text-to-video diffusion models have advanced video generation significantly. However, customizing these models to generate videos with tailored motions presents a substantial challenge. In specific, they encounter hurdles in (a) accurately reproducing motion from a target video, and (b) creating diverse visual variations. For example, straightforward extensions of static image customization methods to video often lead to intricate entanglements of appearance and motion data. To tackle this, here we present the Video Motion Customization (VMC) framework, a novel one-shot tuning approach crafted to adapt temporal attention layers within video diffusion models. Our approach introduces a novel motion distillation objective using residual vectors between consecutive frames as a motion reference. The diffusion process then preserves low-frequency motion trajectories while mitigating high-frequency motion-unrelated noise in image space. We validate our method against state-of-the-art video generative models across diverse real-world motions and contexts. Our codes, data and the project demo can be found at https://video-motion-customization.github.io

https://huggingface.co/discussions/paper/656e90d6e9d3e5f3f7bac053