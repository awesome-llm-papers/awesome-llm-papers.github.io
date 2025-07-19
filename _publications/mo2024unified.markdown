---
layout: publication
title: Unified Video-language Pre-training With Synchronized Audio
authors: Mo et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: mo2024unified
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.07202'}]
tags: [RAG, Training Techniques, Tools, CVPR, Transformer, Model Architecture]
---
Video-language pre-training is a typical and challenging problem that aims at
learning visual and textual representations from large-scale data in a
self-supervised way. Existing pre-training approaches either captured the
correspondence of image-text pairs or utilized temporal ordering of frames.
However, they do not explicitly explore the natural synchronization between
audio and the other two modalities. In this work, we propose an enhanced
framework for Video-Language pre-training with Synchronized Audio, termed as
VLSA, that can learn tri-modal representations in a unified self-supervised
transformer. Specifically, our VLSA jointly aggregates embeddings of local
patches and global tokens for video, text, and audio. Furthermore, we utilize
local-patch masked modeling to learn modality-aware features, and leverage
global audio matching to capture audio-guided features for video and text. We
conduct extensive experiments on retrieval across text, video, and audio. Our
simple model pre-trained on only 0.9M data achieves improving results against
state-of-the-art baselines. In addition, qualitative visualizations vividly
showcase the superiority of our VLSA in learning discriminative visual-textual
representations.