---
layout: publication
title: 'Instructhumans: Editing Animated 3D Human Textures With Instructions'
authors: Zhu Jiayin, Yang Linlin, Yao Angela
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2024
bibkey: zhu2024instructhumans
citations: 150
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.04037'}]
tags: [ICCV, Distillation, Alt, Tools, Efficiency And Optimization, Merging]
---
We present InstructHumans, a novel framework for instruction-driven 3D human
texture editing. Existing text-based editing methods use Score Distillation
Sampling (SDS) to distill guidance from generative models. This work shows that
naively using such scores is harmful to editing as they destroy consistency
with the source avatar. Instead, we propose an alternate SDS for Editing
(SDS-E) that selectively incorporates subterms of SDS across diffusion
timesteps. We further enhance SDS-E with spatial smoothness regularization and
gradient-based viewpoint sampling to achieve high-quality edits with sharp and
high-fidelity detailing. InstructHumans significantly outperforms existing 3D
editing methods, consistent with the initial avatar while faithful to the
textual instructions. Project page: https://jyzhu.top/instruct-humans .