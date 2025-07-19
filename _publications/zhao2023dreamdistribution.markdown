---
layout: publication
title: 'Dreamdistribution: Learning Prompt Distribution For Diverse In-distribution
  Generation'
authors: Zhao et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: zhao2023dreamdistribution
citations: 146
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.14216'}]
tags: [CVPR, Prompting, Evaluation, Merging]
---
The popularization of Text-to-Image (T2I) diffusion models enables the
generation of high-quality images from text descriptions. However, generating
diverse customized images with reference visual attributes remains challenging.
This work focuses on personalizing T2I diffusion models at a more abstract
concept or category level, adapting commonalities from a set of reference
images while creating new instances with sufficient variations. We introduce a
solution that allows a pretrained T2I diffusion model to learn a set of soft
prompts, enabling the generation of novel images by sampling prompts from the
learned distribution. These prompts offer text-guided editing capabilities and
additional flexibility in controlling variation and mixing between multiple
distributions. We also show the adaptability of the learned prompt distribution
to other tasks, such as text-to-3D. Finally we demonstrate effectiveness of our
approach through quantitative analysis including automatic evaluation and human
assessment. Project website: https://briannlongzhao.github.io/DreamDistribution