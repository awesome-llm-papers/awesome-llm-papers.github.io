---
layout: publication
title: "Pixart-\u03B4: Fast And Controllable Image Generation With Latent Consistency\
  \ Models"
authors: Junsong Chen, Yue Wu, Simian Luo, Enze Xie, Sayak Paul, Ping Luo, Hang Zhao,
  Zhenguo Li
conference: No Venue
year: 2024
bibkey: chen2024pixart
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/659f52a1d56cbade8db37144'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2401.05252'}]
tags: ["Model Architecture", "Tools", "Training Techniques"]
short_authors: Chen et al.
---
This technical report introduces PIXART-\{\delta\}, a text-to-image synthesis framework that integrates the Latent Consistency Model (LCM) and ControlNet into the advanced PIXART-\{\alpha\} model. PIXART-\{\alpha\} is recognized for its ability to generate high-quality images of 1024px resolution through a remarkably efficient training process. The integration of LCM in PIXART-\{\delta\} significantly accelerates the inference speed, enabling the production of high-quality images in just 2-4 steps. Notably, PIXART-\{\delta\} achieves a breakthrough 0.5 seconds for generating 1024x1024 pixel images, marking a 7x improvement over the PIXART-\{\alpha\}. Additionally, PIXART-\{\delta\} is designed to be efficiently trainable on 32GB V100 GPUs within a single day. With its 8-bit inference capability (von Platen et al., 2023), PIXART-\{\delta\} can synthesize 1024px images within 8GB GPU memory constraints, greatly enhancing its usability and accessibility. Furthermore, incorporating a ControlNet-like module enables fine-grained control over text-to-image diffusion models. We introduce a novel ControlNet-Transformer architecture, specifically tailored for Transformers, achieving explicit controllability alongside high-quality image generation. As a state-of-the-art, open-source image generation model, PIXART-\{\delta\} offers a promising alternative to the Stable Diffusion family of models, contributing significantly to text-to-image synthesis.

https://huggingface.co/discussions/paper/659f52a1d56cbade8db37144