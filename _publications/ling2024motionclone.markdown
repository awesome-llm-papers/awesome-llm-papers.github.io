---
layout: publication
title: 'Motionclone: Training-free Motion Cloning For Controllable Video Generation'
authors: Pengyang Ling, Jiazi Bu, Pan Zhang, Xiaoyi Dong, Yuhang Zang, Tong Wu, Huaian
  Chen, Jiaqi Wang, Yi Jin
conference: No Venue
year: 2024
bibkey: ling2024motionclone
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/666a7156be667d2b1db1d299'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2406.05338'}]
tags: ["Tools"]
short_authors: Ling et al.
---
Motion-based controllable text-to-video generation involves motions to control the video generation. Previous methods typically require the training of models to encode motion cues or the fine-tuning of video diffusion models. However, these approaches often result in suboptimal motion generation when applied outside the trained domain. In this work, we propose MotionClone, a training-free framework that enables motion cloning from a reference video to control text-to-video generation. We employ temporal attention in video inversion to represent the motions in the reference video and introduce primary temporal-attention guidance to mitigate the influence of noisy or very subtle motions within the attention weights. Furthermore, to assist the generation model in synthesizing reasonable spatial relationships and enhance its prompt-following capability, we propose a location-aware semantic guidance mechanism that leverages the coarse location of the foreground from the reference video and original classifier-free guidance features to guide the video generation. Extensive experiments demonstrate that MotionClone exhibits proficiency in both global camera motion and local object motion, with notable superiority in terms of motion fidelity, textual alignment, and temporal consistency.

https://huggingface.co/discussions/paper/666a7156be667d2b1db1d299