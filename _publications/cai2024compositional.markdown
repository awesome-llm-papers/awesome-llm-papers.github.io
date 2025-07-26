---
layout: publication
title: On The Compositional Generalization Of Multimodal Llms For Medical Imaging
authors: Zhenyang Cai, Junying Chen, Rongsheng Wang, Weihong Wang, Yonglin Deng, Dingjie
  Song, Yize Chen, Zixu Zhang, Benyou Wang
conference: No Venue
year: 2024
bibkey: cai2024compositional
additional_links: [{name: Code, url: 'https://github.com/FreedomIntelligence/Med-MAT'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2412.20070'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Cai et al.
---
Multimodal large language models (MLLMs) hold significant potential in the medical field, but their capabilities are often limited by insufficient data in certain medical domains, highlighting the need for understanding what kinds of images can be used by MLLMs for generalization. Current research suggests that multi-task training outperforms single-task as different tasks can benefit each other, but they often overlook the internal relationships within these tasks, providing limited guidance on selecting datasets to enhance specific tasks. To analyze this phenomenon, we attempted to employ compositional generalization (CG)-the ability of models to understand novel combinations by recombining learned elements-as a guiding framework. Since medical images can be precisely defined by Modality, Anatomical area, and Task, naturally providing an environment for exploring CG. Therefore, we assembled 106 medical datasets to create Med-MAT for comprehensive experiments. The experiments confirmed that MLLMs can use CG to understand unseen medical images and identified CG as one of the main drivers of the generalization observed in multi-task training. Additionally, further studies demonstrated that CG effectively supports datasets with limited data and delivers consistent performance across different backbones, highlighting its versatility and broad applicability. Med-MAT is publicly available at https://github.com/FreedomIntelligence/Med-MAT.

https://huggingface.co/discussions/paper/67735fa09cc5d33bf6af3d85