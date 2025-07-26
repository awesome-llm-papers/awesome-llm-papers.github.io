---
layout: publication
title: 'Javisdit: Joint Audio-video Diffusion Transformer With Hierarchical Spatio-temporal
  Prior Synchronization'
authors: Kai Liu, Wei Li, Lai Chen, Shengqiong Wu, Yanhao Zheng, Jiayi Ji, Fan Zhou,
  Rongxin Jiang, Jiebo Luo, Hao Fei, Tat-seng Chua
conference: No Venue
year: 2025
bibkey: liu2025javisdit
additional_links: [{name: Code, url: 'https://javisdit.github.io/'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/67eea086cdb7049bd6f79e78'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2503.23377'}]
tags: ["Model Architecture"]
short_authors: Liu et al.
---
This paper introduces JavisDiT, a novel Joint Audio-Video Diffusion Transformer designed for synchronized audio-video generation (JAVG). Built upon the powerful Diffusion Transformer (DiT) architecture, JavisDiT is able to generate high-quality audio and video content simultaneously from open-ended user prompts. To ensure optimal synchronization, we introduce a fine-grained spatio-temporal alignment mechanism through a Hierarchical Spatial-Temporal Synchronized Prior (HiST-Sypo) Estimator. This module extracts both global and fine-grained spatio-temporal priors, guiding the synchronization between the visual and auditory components. Furthermore, we propose a new benchmark, JavisBench, consisting of 10,140 high-quality text-captioned sounding videos spanning diverse scenes and complex real-world scenarios. Further, we specifically devise a robust metric for evaluating the synchronization between generated audio-video pairs in real-world complex content. Experimental results demonstrate that JavisDiT significantly outperforms existing methods by ensuring both high-quality generation and precise synchronization, setting a new standard for JAVG tasks. Our code, model, and dataset will be made publicly available at https://javisdit.github.io/.

https://huggingface.co/discussions/paper/67eea086cdb7049bd6f79e78