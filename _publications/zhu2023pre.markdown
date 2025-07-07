---
layout: publication
title: '3d-vista: Pre-trained Transformer For 3D Vision And Text Alignment'
authors: Ziyu Zhu et al.
conference: Arxiv
year: 2023
citations: 36
bibkey: zhu2023pre
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.04352'}]
tags: [Training Techniques, Transformer, GPT, Merging, Pre-Training, Reinforcement
    Learning, Fine-Tuning, Attention Mechanism, Efficiency and Optimization, Multimodal
    Models, Model Architecture]
---
3D vision-language grounding (3D-VL) is an emerging field that aims to
connect the 3D physical world with natural language, which is crucial for
achieving embodied intelligence. Current 3D-VL models rely heavily on
sophisticated modules, auxiliary losses, and optimization tricks, which calls
for a simple and unified model. In this paper, we propose 3D-VisTA, a
pre-trained Transformer for 3D Vision and Text Alignment that can be easily
adapted to various downstream tasks. 3D-VisTA simply utilizes self-attention
layers for both single-modal modeling and multi-modal fusion without any
sophisticated task-specific design. To further enhance its performance on 3D-VL
tasks, we construct ScanScribe, the first large-scale 3D scene-text pairs
dataset for 3D-VL pre-training. ScanScribe contains 2,995 RGB-D scans for 1,185
unique indoor scenes originating from ScanNet and 3R-Scan datasets, along with
paired 278K scene descriptions generated from existing 3D-VL tasks, templates,
and GPT-3. 3D-VisTA is pre-trained on ScanScribe via masked language/object
modeling and scene-text matching. It achieves state-of-the-art results on
various 3D-VL tasks, ranging from visual grounding and dense captioning to
question answering and situated reasoning. Moreover, 3D-VisTA demonstrates
superior data efficiency, obtaining strong performance even with limited
annotations during downstream task fine-tuning.