---
layout: publication
title: 'FLAVARS: A Multimodal Foundational Language And Vision Alignment Model For
  Remote Sensing'
authors: Corley et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: corley2025flavars
citations: 260
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.08490'}]
tags: [CVPR, Multimodal Models, Training Techniques]
---
Remote sensing imagery is dense with objects and contextual visual
information. There is a recent trend to combine paired satellite images and
text captions for pretraining performant encoders for downstream tasks.
However, while contrastive image-text methods like CLIP enable vision-language
alignment and zero-shot classification ability, vision-only downstream
performance tends to degrade compared to image-only pretraining, such as MAE.
In this paper, we propose FLAVARS, a pretraining method that combines the best
of both contrastive learning and masked modeling, along with geospatial
alignment via contrastive location encoding. We find that FLAVARS significantly
outperforms a baseline of SkyCLIP for vision-only tasks such as KNN
classification and semantic segmentation, +6% mIOU on SpaceNet1, while
retaining the ability to perform zero-shot classification, unlike MAE
pretrained methods.