---
layout: publication
title: 'MASTER: Multimodal Segmentation With Text Prompts'
authors: Liu et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: liu2025master
citations: 286
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.04199'}]
tags: [RAG, Prompting, Evaluation, CVPR, Model Architecture, Multimodal Models, Datasets,
  Merging]
---
RGB-Thermal fusion is a potential solution for various weather and light
conditions in challenging scenarios. However, plenty of studies focus on
designing complex modules to fuse different modalities. With the widespread
application of large language models (LLMs), valuable information can be more
effectively extracted from natural language. Therefore, we aim to leverage the
advantages of large language models to design a structurally simple and highly
adaptable multimodal fusion model architecture. We proposed MultimodAl
Segmentation with TExt PRompts (MASTER) architecture, which integrates LLM into
the fusion of RGB-Thermal multimodal data and allows complex query text to
participate in the fusion process. Our model utilizes a dual-path structure to
extract information from different modalities of images. Additionally, we
employ LLM as the core module for multimodal fusion, enabling the model to
generate learnable codebook tokens from RGB, thermal images, and textual
information. A lightweight image decoder is used to obtain semantic
segmentation results. The proposed MASTER performs exceptionally well in
benchmark tests across various automated driving scenarios, yielding promising
results.