---
layout: publication
title: 'Meta-transformer: A Unified Framework For Multimodal Learning'
authors: Yiyuan Zhang, Kaixiong Gong, Kaipeng Zhang, Hongsheng Li, Yu Qiao, Wanli
  Ouyang, Xiangyu Yue
conference: No Venue
year: 2023
bibkey: zhang2023meta
additional_links: [{name: Code, url: 'https://github.com/invictus717/MetaTransformer'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/64ba0b18b7af2cf5151abc53'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2307.10802'}]
tags: ["Model Architecture"]
short_authors: Zhang et al.
---
Multimodal learning aims to build models that can process and relate information from multiple modalities. Despite years of development in this field, it still remains challenging to design a unified network for processing various modalities (e.g. natural language, 2D images, 3D point clouds, audio, video, time series, tabular data) due to the inherent gaps among them. In this work, we propose a framework, named Meta-Transformer, that leverages a frozen encoder to perform multimodal perception without any paired multimodal training data. In Meta-Transformer, the raw input data from various modalities are mapped into a shared token space, allowing a subsequent encoder with frozen parameters to extract high-level semantic features of the input data. Composed of three main components: a unified data tokenizer, a modality-shared encoder, and task-specific heads for downstream tasks, Meta-Transformer is the first framework to perform unified learning across 12 modalities with unpaired data. Experiments on different benchmarks reveal that Meta-Transformer can handle a wide range of tasks including fundamental perception (text, image, point cloud, audio, video), practical application (X-Ray, infrared, hyperspectral, and IMU), and data mining (graph, tabular, and time-series). Meta-Transformer indicates a promising future for developing unified multimodal intelligence with transformers. Code will be available at https://github.com/invictus717/MetaTransformer

https://huggingface.co/discussions/paper/64ba0b18b7af2cf5151abc53