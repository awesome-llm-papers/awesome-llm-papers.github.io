---
layout: publication
title: Visual Grounding With Attention-driven Constraint Balancing
authors: Kang et al.
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2024
bibkey: kang2024visual
citations: 127
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.03243'}]
tags: [Attention Mechanism, Tools, Evaluation, CVPR, Transformer, Model Architecture,
  Datasets]
---
Unlike Object Detection, Visual Grounding task necessitates the detection of
an object described by complex free-form language. To simultaneously model such
complex semantic and visual representations, recent state-of-the-art studies
adopt transformer-based models to fuse features from both modalities, further
introducing various modules that modulate visual features to align with the
language expressions and eliminate the irrelevant redundant information.
However, their loss function, still adopting common Object Detection losses,
solely governs the bounding box regression output, failing to fully optimize
for the above objectives. To tackle this problem, in this paper, we first
analyze the attention mechanisms of transformer-based models. Building upon
this, we further propose a novel framework named Attention-Driven Constraint
Balancing (AttBalance) to optimize the behavior of visual features within
language-relevant regions. Extensive experimental results show that our method
brings impressive improvements. Specifically, we achieve constant improvements
over five different models evaluated on four different benchmarks. Moreover, we
attain a new state-of-the-art performance by integrating our method into QRNet.