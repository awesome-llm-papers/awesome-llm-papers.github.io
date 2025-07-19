---
layout: publication
title: Tuning-free Visual Customization Via View Iterative Self-attention Control
authors: Li et al.
conference: Artificial Intelligence
year: 2024
bibkey: li2024tuning
citations: 851
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.06258'}]
tags: [Training Techniques, Attention Mechanism, IJCAI, Transformer, Model Architecture,
  AISTATS, Reinforcement Learning, Applications, Fine Tuning, UAI, AAAI, Merging]
---
Fine-Tuning Diffusion Models enable a wide range of personalized generation
and editing applications on diverse visual modalities. While Low-Rank
Adaptation (LoRA) accelerates the fine-tuning process, it still requires
multiple reference images and time-consuming training, which constrains its
scalability for large-scale and real-time applications. In this paper, we
propose \textit\{View Iterative Self-Attention Control (VisCtrl)\} to tackle this
challenge. Specifically, VisCtrl is a training-free method that injects the
appearance and structure of a user-specified subject into another subject in
the target image, unlike previous approaches that require fine-tuning the
model. Initially, we obtain the initial noise for both the reference and target
images through DDIM inversion. Then, during the denoising phase, features from
the reference image are injected into the target image via the self-attention
mechanism. Notably, by iteratively performing this feature injection process,
we ensure that the reference image features are gradually integrated into the
target image. This approach results in consistent and harmonious editing with
only one reference image in a few denoising steps. Moreover, benefiting from
our plug-and-play architecture design and the proposed Feature Gradual Sampling
strategy for multi-view editing, our method can be easily extended to edit in
complex visual domains. Extensive experiments show the efficacy of VisCtrl
across a spectrum of tasks, including personalized editing of images, videos,
and 3D scenes.