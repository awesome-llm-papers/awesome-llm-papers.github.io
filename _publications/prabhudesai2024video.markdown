---
layout: publication
title: Video Diffusion Alignment Via Reward Gradients
authors: Mihir Prabhudesai, Russell Mendonca, Zheyang Qin, Katerina Fragkiadaki, Deepak
  Pathak
conference: No Venue
year: 2024
bibkey: prabhudesai2024video
additional_links: [{name: Code, url: 'https://vader-vid.github.io'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/6690952468b20cd8e62a7dc9'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2407.08737'}]
tags: ["Reinforcement Learning"]
short_authors: Prabhudesai et al.
---
We have made significant progress towards building foundational video diffusion models. As these models are trained using large-scale unsupervised data, it has become crucial to adapt these models to specific downstream tasks. Adapting these models via supervised fine-tuning requires collecting target datasets of videos, which is challenging and tedious. In this work, we utilize pre-trained reward models that are learned via preferences on top of powerful vision discriminative models to adapt video diffusion models. These models contain dense gradient information with respect to generated RGB pixels, which is critical to efficient learning in complex search spaces, such as videos. We show that backpropagating gradients from these reward models to a video diffusion model can allow for compute and sample efficient alignment of the video diffusion model. We show results across a variety of reward models and video diffusion models, demonstrating that our approach can learn much more efficiently in terms of reward queries and computation than prior gradient-free approaches. Our code, model weights,and more visualization are available at https://vader-vid.github.io.

https://huggingface.co/discussions/paper/6690952468b20cd8e62a7dc9