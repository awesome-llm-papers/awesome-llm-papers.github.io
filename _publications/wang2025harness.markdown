---
layout: publication
title: 'Harness Local Rewards For Global Benefits: Effective Text-to-video Generation
  Alignment With Patch-level Reward Models'
authors: Wang et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: wang2025harness
citations: 140
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.06812'}]
tags: [Training Techniques, GPT, CVPR, Evaluation, Model Architecture, Efficiency
    And Optimization, Reinforcement Learning, Merging]
---
The emergence of diffusion models (DMs) has significantly improved the
quality of text-to-video generation models (VGMs). However, current VGM
optimization primarily emphasizes the global quality of videos, overlooking
localized errors, which leads to suboptimal generation capabilities. To address
this issue, we propose a post-training strategy for VGMs, HALO, which
explicitly incorporates local feedback from a patch reward model, providing
detailed and comprehensive training signals with the video reward model for
advanced VGM optimization. To develop an effective patch reward model, we
distill GPT-4o to continuously train our video reward model, which enhances
training efficiency and ensures consistency between video and patch reward
distributions. Furthermore, to harmoniously integrate patch rewards into VGM
optimization, we introduce a granular DPO (Gran-DPO) algorithm for DMs,
allowing collaborative use of both patch and video rewards during the
optimization process. Experimental results indicate that our patch reward model
aligns well with human annotations and HALO substantially outperforms the
baselines across two evaluation methods. Further experiments quantitatively
prove the existence of patch defects, and our proposed method could effectively
alleviate this issue.