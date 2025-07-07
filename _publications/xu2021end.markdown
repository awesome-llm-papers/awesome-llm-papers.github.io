---
layout: publication
title: 'E2E-VLP: End-to-end Vision-language Pre-training Enhanced By Visual Learning'
authors: Haiyang Xu et al.
conference: Arxiv
year: 2021
citations: 44
bibkey: xu2021end
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.01804'}]
tags: [Training Techniques, Transformer, Pre-Training, Tools, Efficiency and Optimization,
  Multimodal Models, Model Architecture]
---
Vision-language pre-training (VLP) on large-scale image-text pairs has
achieved huge success for the cross-modal downstream tasks. The most existing
pre-training methods mainly adopt a two-step training procedure, which firstly
employs a pre-trained object detector to extract region-based visual features,
then concatenates the image representation and text embedding as the input of
Transformer to train. However, these methods face problems of using
task-specific visual representation of the specific object detector for generic
cross-modal understanding, and the computation inefficiency of two-stage
pipeline. In this paper, we propose the first end-to-end vision-language
pre-trained model for both V+L understanding and generation, namely E2E-VLP,
where we build a unified Transformer framework to jointly learn visual
representation, and semantic alignments between image and text. We incorporate
the tasks of object detection and image captioning into pre-training with a
unified Transformer encoder-decoder architecture for enhancing visual learning.
An extensive set of experiments have been conducted on well-established
vision-language downstream tasks to demonstrate the effectiveness of this novel
VLP paradigm.