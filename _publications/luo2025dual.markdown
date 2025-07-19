---
layout: publication
title: Dual-process Image Generation
authors: Luo et al.
conference: Applied Optics
year: 2025
bibkey: luo2025dual
citations: 223
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.01955'}]
tags: [Distillation, Prompting, Tools, Efficiency And Optimization, Applications,
  Multimodal Models]
---
Prior methods for controlling image generation are limited in their ability to be taught new tasks. In contrast, vision-language models, or VLMs, can learn tasks in-context and produce the correct outputs for a given input. We propose a dual-process distillation scheme that allows feed-forward image generators to learn new tasks from deliberative VLMs. Our scheme uses a VLM to rate the generated images and backpropagates this gradient to update the weights of the image generator. Our general framework enables a wide variety of new control tasks through the same text-and-image based interface. We showcase a handful of applications of this technique for different types of control signals, such as commonsense inferences and visual prompts. With our method, users can implement multimodal controls for properties such as color palette, line weight, horizon position, and relative depth within a matter of minutes. Project page: https://dual-process.github.io.