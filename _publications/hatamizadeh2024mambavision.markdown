---
layout: publication
title: 'Mambavision: A Hybrid Mamba-transformer Vision Backbone'
authors: Ali Hatamizadeh, Jan Kautz
conference: No Venue
year: 2024
bibkey: hatamizadeh2024mambavision
additional_links: [{name: Code, url: 'https://github.com/NVlabs/MambaVision'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/66908c6bb70d356ed3bd35dd'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2407.08083'}]
tags: ["Model Architecture"]
short_authors: Ali Hatamizadeh, Jan Kautz
---
We propose a novel hybrid Mamba-Transformer backbone, denoted as MambaVision, which is specifically tailored for vision applications. Our core contribution includes redesigning the Mamba formulation to enhance its capability for efficient modeling of visual features. In addition, we conduct a comprehensive ablation study on the feasibility of integrating Vision Transformers (ViT) with Mamba. Our results demonstrate that equipping the Mamba architecture with several self-attention blocks at the final layers greatly improves the modeling capacity to capture long-range spatial dependencies. Based on our findings, we introduce a family of MambaVision models with a hierarchical architecture to meet various design criteria. For Image classification on ImageNet-1K dataset, MambaVision model variants achieve a new State-of-the-Art (SOTA) performance in terms of Top-1 accuracy and image throughput. In downstream tasks such as object detection, instance segmentation and semantic segmentation on MS COCO and ADE20K datasets, MambaVision outperforms comparably-sized backbones and demonstrates more favorable performance. Code: https://github.com/NVlabs/MambaVision.

https://huggingface.co/discussions/paper/66908c6bb70d356ed3bd35dd