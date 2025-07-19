---
layout: publication
title: Robust Latent Representation Tuning For Image-text Classification
authors: Sun Hao, Song Yu
conference: IEEE Transactions on Neural Networks and Learning Systems
year: 2024
bibkey: sun2024robust
citations: 86
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.06048'}]
tags: [Training Techniques, Tools, Multimodal Models, Datasets, Merging]
---
Large models have demonstrated exceptional generalization capabilities in
computer vision and natural language processing. Recent efforts have focused on
enhancing these models with multimodal processing abilities. However,
addressing the challenges posed by scenarios where one modality is absent
remains a significant hurdle. In response to this issue, we propose a robust
latent representation tuning method for large models. Specifically, our
approach introduces a modality latent translation module to maximize the
correlation between modalities, resulting in a robust representation. Following
this, a newly designed fusion module is employed to facilitate information
interaction between the modalities. Within this framework, common semantics are
refined during training, and robust performance is achieved even in the absence
of one modality. Importantly, our method maintains the frozen state of the
image and text foundation models to preserve their capabilities acquired
through large-scale pretraining. We conduct experiments on several public
datasets, and the results underscore the effectiveness of our proposed method.