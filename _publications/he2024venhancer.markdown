---
layout: publication
title: 'Venhancer: Generative Space-time Enhancement For Video Generation'
authors: He et al.
conference: 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: he2024venhancer
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.07667'}]
tags: [Training Techniques, Tools, CVPR, Evaluation, Datasets, Merging]
---
We present VEnhancer, a generative space-time enhancement framework that
improves the existing text-to-video results by adding more details in spatial
domain and synthetic detailed motion in temporal domain. Given a generated
low-quality video, our approach can increase its spatial and temporal
resolution simultaneously with arbitrary up-sampling space and time scales
through a unified video diffusion model. Furthermore, VEnhancer effectively
removes generated spatial artifacts and temporal flickering of generated
videos. To achieve this, basing on a pretrained video diffusion model, we train
a video ControlNet and inject it to the diffusion model as a condition on low
frame-rate and low-resolution videos. To effectively train this video
ControlNet, we design space-time data augmentation as well as video-aware
conditioning. Benefiting from the above designs, VEnhancer yields to be stable
during training and shares an elegant end-to-end training manner. Extensive
experiments show that VEnhancer surpasses existing state-of-the-art video
super-resolution and space-time super-resolution methods in enhancing
AI-generated videos. Moreover, with VEnhancer, exisiting open-source
state-of-the-art text-to-video method, VideoCrafter-2, reaches the top one in
video generation benchmark -- VBench.