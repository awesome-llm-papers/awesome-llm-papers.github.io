---
layout: publication
title: 'Comp: Continual Multimodal Pre-training For Vision Foundation Models'
authors: Yitong Chen, Lingchen Meng, Wujian Peng, Zuxuan Wu, Yu-gang Jiang
conference: No Venue
year: 2025
bibkey: chen2025comp
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.18931'}]
tags: ["Evaluation", "Training Techniques"]
short_authors: Chen et al.
---
Pre-trained Vision Foundation Models (VFMs) provide strong visual representations for a wide range of applications. In this paper, we continually pre-train prevailing VFMs in a multimodal manner such that they can effortlessly process visual inputs of varying sizes and produce visual representations that are more aligned with language representations, regardless of their original pre-training process. To this end, we introduce CoMP, a carefully designed multimodal pre-training pipeline. CoMP uses a Continual Rotary Position Embedding to support native resolution continual pre-training, and an Alignment Loss between visual and textual features through language prototypes to align multimodal representations. By three-stage training, our VFMs achieve remarkable improvements not only in multimodal understanding but also in other downstream tasks such as classification and segmentation. Remarkably, CoMP-SigLIP achieves scores of 66.7 on ChartQA and 75.9 on DocVQA with a 0.5B LLM, while maintaining an 87.4% accuracy on ImageNet-1K and a 49.5 mIoU on ADE20K under frozen chunk evaluation.

https://huggingface.co/discussions/paper/67e25c4f1908043170bd55a8