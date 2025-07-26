---
layout: publication
title: Towards Physically Plausible Video Generation Via VLM Planning
authors: Xindi Yang, Baolu Li, Yiming Zhang, Zhenfei Yin, Lei Bai, Liqian Ma, Zhiyong
  Wang, Jianfei Cai, Tien-tsin Wong, Huchuan Lu, Xu Jia
conference: No Venue
year: 2025
bibkey: yang2025towards
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.23368'}]
tags: ["Has Code", "Tools"]
short_authors: Yang et al.
---
Video diffusion models (VDMs) have advanced significantly in recent years, enabling the generation of highly realistic videos and drawing the attention of the community in their potential as world simulators. However, despite their capabilities, VDMs often fail to produce physically plausible videos due to an inherent lack of understanding of physics, resulting in incorrect dynamics and event sequences. To address this limitation, we propose a novel two-stage image-to-video generation framework that explicitly incorporates physics. In the first stage, we employ a Vision Language Model (VLM) as a coarse-grained motion planner, integrating chain-of-thought and physics-aware reasoning to predict a rough motion trajectories/changes that approximate real-world physical dynamics while ensuring the inter-frame consistency. In the second stage, we use the predicted motion trajectories/changes to guide the video generation of a VDM. As the predicted motion trajectories/changes are rough, noise is added during inference to provide freedom to the VDM in generating motion with more fine details. Extensive experimental results demonstrate that our framework can produce physically plausible motion, and comparative evaluations highlight the notable superiority of our approach over existing methods. More video results are available on our Project Page: https://madaoer.github.io/projects/physically_plausible_video_generation.

https://huggingface.co/discussions/paper/67ee6cf0153d50e65e63d093