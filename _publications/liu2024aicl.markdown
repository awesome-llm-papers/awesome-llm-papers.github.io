---
layout: publication
title: 'AICL: Action In-context Learning For Video Diffusion Model'
authors: Liu et al.
conference: 2019 IEEE Winter Conference on Applications of Computer Vision (WACV)
year: 2024
bibkey: liu2024aicl
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.11535'}]
tags: [Training Techniques, Evaluation, In Context Learning, Applications, Datasets,
  Merging]
---
The open-domain video generation models are constrained by the scale of the
training video datasets, and some less common actions still cannot be
generated. Some researchers explore video editing methods and achieve action
generation by editing the spatial information of the same action video.
However, this method mechanically generates identical actions without
understanding, which does not align with the characteristics of open-domain
scenarios. In this paper, we propose AICL, which empowers the generative model
with the ability to understand action information in reference videos, similar
to how humans do, through in-context learning. Extensive experiments
demonstrate that AICL effectively captures the action and achieves
state-of-the-art generation performance across three typical video diffusion
models on five metrics when using randomly selected categories from
non-training datasets.