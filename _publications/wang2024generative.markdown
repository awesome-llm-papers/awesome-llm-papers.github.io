---
layout: publication
title: 'Generative Inbetweening: Adapting Image-to-video Models For Keyframe Interpolation'
authors: Xiaojuan Wang, Boyang Zhou, Brian Curless, Ira Kemelmacher-shlizerman, Aleksander
  Holynski, Steven M. Seitz
conference: No Venue
year: 2024
bibkey: wang2024generative
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2408.15239'}]
tags: ["Fine-Tuning"]
short_authors: Wang et al.
---
We present a method for generating video sequences with coherent motion between a pair of input key frames. We adapt a pretrained large-scale image-to-video diffusion model (originally trained to generate videos moving forward in time from a single input image) for key frame interpolation, i.e., to produce a video in between two input frames. We accomplish this adaptation through a lightweight fine-tuning technique that produces a version of the model that instead predicts videos moving backwards in time from a single input image. This model (along with the original forward-moving model) is subsequently used in a dual-directional diffusion sampling process that combines the overlapping model estimates starting from each of the two keyframes. Our experiments show that our method outperforms both existing diffusion-based methods and traditional frame interpolation techniques.

https://huggingface.co/discussions/paper/66ce96f16116c7f53e64c694