---
layout: publication
title: 'Splattalk: 3D VQA With Gaussian Splatting'
authors: Thai et al.
conference: 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: thai2025splattalk
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.06271'}]
tags: [Tools, Evaluation, CVPR, Applications, Multimodal Models, Datasets]
---
Language-guided 3D scene understanding is important for advancing
applications in robotics, AR/VR, and human-computer interaction, enabling
models to comprehend and interact with 3D environments through natural
language. While 2D vision-language models (VLMs) have achieved remarkable
success in 2D VQA tasks, progress in the 3D domain has been significantly
slower due to the complexity of 3D data and the high cost of manual
annotations. In this work, we introduce SplatTalk, a novel method that uses a
generalizable 3D Gaussian Splatting (3DGS) framework to produce 3D tokens
suitable for direct input into a pretrained LLM, enabling effective zero-shot
3D visual question answering (3D VQA) for scenes with only posed images. During
experiments on multiple benchmarks, our approach outperforms both 3D models
trained specifically for the task and previous 2D-LMM-based models utilizing
only images (our setting), while achieving competitive performance with
state-of-the-art 3D LMMs that additionally utilize 3D inputs.