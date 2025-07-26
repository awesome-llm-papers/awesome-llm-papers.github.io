---
layout: publication
title: 'Align Your Latents: High-resolution Video Synthesis With Latent Diffusion
  Models'
authors: Andreas Blattmann, Robin Rombach, Huan Ling, Tim Dockhorn, Seung Wook Kim,
  Sanja Fidler, Karsten Kreis
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: blattmann2023align
citations: 280
additional_links: [{name: Code, url: 'https://research.nvidia.com/labs/toronto-ai/VideoLDM/'},
  {name: Paper, url: 'https://arxiv.org/abs/2304.08818'}]
tags: ["CVPR"]
short_authors: Blattmann et al.
---
Latent Diffusion Models (LDMs) enable high-quality image synthesis while
avoiding excessive compute demands by training a diffusion model in a
compressed lower-dimensional latent space. Here, we apply the LDM paradigm to
high-resolution video generation, a particularly resource-intensive task. We
first pre-train an LDM on images only; then, we turn the image generator into a
video generator by introducing a temporal dimension to the latent space
diffusion model and fine-tuning on encoded image sequences, i.e., videos.
Similarly, we temporally align diffusion model upsamplers, turning them into
temporally consistent video super resolution models. We focus on two relevant
real-world applications: Simulation of in-the-wild driving data and creative
content creation with text-to-video modeling. In particular, we validate our
Video LDM on real driving videos of resolution 512 x 1024, achieving
state-of-the-art performance. Furthermore, our approach can easily leverage
off-the-shelf pre-trained image LDMs, as we only need to train a temporal
alignment model in that case. Doing so, we turn the publicly available,
state-of-the-art text-to-image LDM Stable Diffusion into an efficient and
expressive text-to-video model with resolution up to 1280 x 2048. We show that
the temporal layers trained in this way generalize to different fine-tuned
text-to-image LDMs. Utilizing this property, we show the first results for
personalized text-to-video generation, opening exciting directions for future
content creation. Project page:
https://research.nvidia.com/labs/toronto-ai/VideoLDM/