---
layout: publication
title: 'Voco-llama: Towards Vision Compression With Large Language Models'
authors: Xubing Ye, Yukang Gan, Xiaoke Huang, Yixiao Ge, Ying Shan, Yansong Tang
conference: No Venue
year: 2024
bibkey: ye2024voco
additional_links: [{name: Code, url: 'https://yxxxb.github.io/VoCo-LLaMA-page/\{this'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/66724f17cec66c5343fb595d'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2406.12275'}]
tags: ["Applications", "Efficiency", "Has Code", "Training Techniques"]
short_authors: Ye et al.
---
Vision-Language Models (VLMs) have achieved remarkable success in various multi-modal tasks, but they are often bottlenecked by the limited context window and high computational cost of processing high-resolution image inputs and videos. Vision compression can alleviate this problem by reducing the vision token count. Previous approaches compress vision tokens with external modules and force LLMs to understand the compressed ones, leading to visual information loss. However, the LLMs' understanding paradigm of vision tokens is not fully utilised in the compression learning process. We propose VoCo-LLaMA, the first approach to compress vision tokens using LLMs. By introducing Vision Compression tokens during the vision instruction tuning phase and leveraging attention distillation, our method distill how LLMs comprehend vision tokens into their processing of VoCo tokens. VoCo-LLaMA facilitates effective vision compression and improves the computational efficiency during the inference stage. Specifically, our method achieves minimal performance loss with a compression ratio of 576times, resulting in up to 94.8% fewer FLOPs and 69.6% acceleration in inference time. Furthermore, through continuous training using time-series compressed token sequences of video frames, VoCo-LLaMA demonstrates the ability to understand temporal correlations, outperforming previous methods on popular video question-answering benchmarks. Our approach presents a promising way to unlock the full potential of VLMs' contextual window, enabling more scalable multi-modal applications. The project page, along with the associated code, can be accessed via https://yxxxb.github.io/VoCo-LLaMA-page/\{this https URL\}.

https://huggingface.co/discussions/paper/66724f17cec66c5343fb595d