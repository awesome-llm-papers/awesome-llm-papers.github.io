---
layout: publication
title: 'Omnigen2: Exploration To Advanced Multimodal Generation'
authors: Chenyuan Wu, Pengfei Zheng, Ruiran Yan, Shitao Xiao, Xin Luo, Yueze Wang,
  Wanli Li, Xiyan Jiang, Yexin Liu, Junjie Zhou, Ze Liu, Ziyi Xia, Chaofan Li, Haoge
  Deng, Jiahao Wang, Kun Luo, Bo Zhang, Defu Lian, Xinlong Wang, Zhongyuan Wang, Tiejun
  Huang, Zheng Liu
conference: No Venue
year: 2025
bibkey: wu2025omnigen2
additional_links: [{name: Code, url: 'https://vectorspacelab.github.io/OmniGen2;'},
  {name: Code, url: 'https://github.com/VectorSpaceLab/OmniGen2'}, {name: Code, url: 'https://huggingface.co/discussions/paper/685a0be90e4ad7e21975850a'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.18871'}]
tags: ["Datasets", "Evaluation", "Has Code", "Training Techniques"]
short_authors: Wu et al.
---
In this work, we introduce OmniGen2, a versatile and open-source generative model designed to provide a unified solution for diverse generation tasks, including text-to-image, image editing, and in-context generation. Unlike OmniGen v1, OmniGen2 features two distinct decoding pathways for text and image modalities, utilizing unshared parameters and a decoupled image tokenizer. This design enables OmniGen2 to build upon existing multimodal understanding models without the need to re-adapt VAE inputs, thereby preserving the original text generation capabilities. To facilitate the training of OmniGen2, we developed comprehensive data construction pipelines, encompassing image editing and in-context generation data. Additionally, we introduce a reflection mechanism tailored for image generation tasks and curate a dedicated reflection dataset based on OmniGen2. Despite its relatively modest parameter size, OmniGen2 achieves competitive results on multiple task benchmarks, including text-to-image and image editing. To further evaluate in-context generation, also referred to as subject-driven tasks, we introduce a new benchmark named OmniContext. OmniGen2 achieves state-of-the-art performance among open-source models in terms of consistency. We will release our models, training code, datasets, and data construction pipeline to support future research in this field. Project Page: https://vectorspacelab.github.io/OmniGen2; GitHub Link: https://github.com/VectorSpaceLab/OmniGen2

https://huggingface.co/discussions/paper/685a0be90e4ad7e21975850a