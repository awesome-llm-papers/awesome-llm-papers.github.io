---
layout: publication
title: Unleashing Text-to-image Diffusion Models For Visual Perception
authors: Zhao et al.
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2023
bibkey: zhao2023unleashing
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.02153'}]
tags: [ICCV, Training Techniques, Attention Mechanism, Prompting, Tools, Evaluation,
  Model Architecture, Multimodal Models, Datasets, Merging]
---
Diffusion models (DMs) have become the new trend of generative models and
have demonstrated a powerful ability of conditional synthesis. Among those,
text-to-image diffusion models pre-trained on large-scale image-text pairs are
highly controllable by customizable prompts. Unlike the unconditional
generative models that focus on low-level attributes and details, text-to-image
diffusion models contain more high-level knowledge thanks to the
vision-language pre-training. In this paper, we propose VPD (Visual Perception
with a pre-trained Diffusion model), a new framework that exploits the semantic
information of a pre-trained text-to-image diffusion model in visual perception
tasks. Instead of using the pre-trained denoising autoencoder in a
diffusion-based pipeline, we simply use it as a backbone and aim to study how
to take full advantage of the learned knowledge. Specifically, we prompt the
denoising decoder with proper textual inputs and refine the text features with
an adapter, leading to a better alignment to the pre-trained stage and making
the visual contents interact with the text prompts. We also propose to utilize
the cross-attention maps between the visual features and the text features to
provide explicit guidance. Compared with other pre-training methods, we show
that vision-language pre-trained diffusion models can be faster adapted to
downstream visual perception tasks using the proposed VPD. Extensive
experiments on semantic segmentation, referring image segmentation and depth
estimation demonstrates the effectiveness of our method. Notably, VPD attains
0.254 RMSE on NYUv2 depth estimation and 73.3% oIoU on RefCOCO-val referring
image segmentation, establishing new records on these two benchmarks. Code is
available at https://github.com/wl-zhao/VPD