---
layout: publication
title: Large-scale Reinforcement Learning For Diffusion Models
authors: Yinan Zhang, Eric Tzeng, Yilun Du, Dmitry Kislyuk
conference: No Venue
year: 2024
bibkey: zhang2024large
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2401.12244'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Zhang et al.
---
Text-to-image diffusion models are a class of deep generative models that have demonstrated an impressive capacity for high-quality image generation. However, these models are susceptible to implicit biases that arise from web-scale text-image training pairs and may inaccurately model aspects of images we care about. This can result in suboptimal samples, model bias, and images that do not align with human ethics and preferences. In this paper, we present an effective scalable algorithm to improve diffusion models using Reinforcement Learning (RL) across a diverse set of reward functions, such as human preference, compositionality, and fairness over millions of images. We illustrate how our approach substantially outperforms existing methods for aligning diffusion models with human preferences. We further illustrate how this substantially improves pretrained Stable Diffusion (SD) models, generating samples that are preferred by humans 80.3% of the time over those from the base SD model while simultaneously improving both the composition and diversity of generated samples.

https://huggingface.co/discussions/paper/65b071e67febbcc2afc9de9e