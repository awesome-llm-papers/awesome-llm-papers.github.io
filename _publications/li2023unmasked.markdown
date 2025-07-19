---
layout: publication
title: 'Unmasked Teacher: Towards Training-efficient Video Foundation Models'
authors: Li et al.
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2023
bibkey: li2023unmasked
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.16058'}]
tags: [ICCV, Training Techniques, Alt, Tools, Efficiency And Optimization, Fine Tuning,
  Multimodal Models]
---
Video Foundation Models (VFMs) have received limited exploration due to high
computational costs and data scarcity. Previous VFMs rely on Image Foundation
Models (IFMs), which face challenges in transferring to the video domain.
Although VideoMAE has trained a robust ViT from limited data, its low-level
reconstruction poses convergence difficulties and conflicts with high-level
cross-modal alignment. This paper proposes a training-efficient method for
temporal-sensitive VFMs that integrates the benefits of existing methods. To
increase data efficiency, we mask out most of the low-semantics video tokens,
but selectively align the unmasked tokens with IFM, which serves as the
UnMasked Teacher (UMT). By providing semantic guidance, our method enables
faster convergence and multimodal friendliness. With a progressive pre-training
framework, our model can handle various tasks including scene-related,
temporal-related, and complex video-language understanding. Using only public
sources for pre-training in 6 days on 32 A100 GPUs, our scratch-built ViT-L/16
achieves state-of-the-art performances on various video tasks. The code and
models will be released at https://github.com/OpenGVLab/unmasked_teacher.