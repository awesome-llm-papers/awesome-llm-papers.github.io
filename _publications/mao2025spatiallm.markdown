---
layout: publication
title: 'Spatiallm: Training Large Language Models For Structured Indoor Modeling'
authors: Yongsen Mao, Junhao Zhong, Chuan Fang, Jia Zheng, Rui Tang, Hao Zhu, Ping
  Tan, Zihan Zhou
conference: No Venue
year: 2025
bibkey: mao2025spatiallm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.07491'}]
tags: ["Applications", "Datasets", "Model Architecture", "Training Techniques"]
short_authors: Mao et al.
---
SpatialLM is a large language model designed to process 3D point cloud data and generate structured 3D scene understanding outputs. These outputs include architectural elements like walls, doors, windows, and oriented object boxes with their semantic categories. Unlike previous methods which exploit task-specific network designs, our model adheres to the standard multimodal LLM architecture and is fine-tuned directly from open-source LLMs. To train SpatialLM, we collect a large-scale, high-quality synthetic dataset consisting of the point clouds of 12,328 indoor scenes (54,778 rooms) with ground-truth 3D annotations, and conduct a careful study on various modeling and training decisions. On public benchmarks, our model gives state-of-the-art performance in layout estimation and competitive results in 3D object detection. With that, we show a feasible path for enhancing the spatial understanding capabilities of modern LLMs for applications in augmented reality, embodied robotics, and more.

https://huggingface.co/discussions/paper/684799083ec10bdd8ab4de92