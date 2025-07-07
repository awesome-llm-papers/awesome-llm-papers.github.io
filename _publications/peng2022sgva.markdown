---
layout: publication
title: 'Sgva-clip: Semantic-guided Visual Adapting Of Vision-language Models For Few-shot
  Image Classification'
authors: Fang Peng, Xiaoshan Yang, Linhui Xiao, Yaowei Wang, Changsheng Xu
conference: Arxiv
year: 2022
citations: 22
bibkey: peng2022sgva
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.16191'}]
tags: [Distillation, Training Techniques, Pre-Training, Few-Shot, Tools, Reinforcement
    Learning, Attention Mechanism, Efficiency and Optimization, Multimodal Models,
  Model Architecture]
---
Although significant progress has been made in few-shot learning, most of
existing few-shot image classification methods require supervised pre-training
on a large amount of samples of base classes, which limits their generalization
ability in real world application. Recently, large-scale Vision-Language
Pre-trained models (VLPs) have been gaining increasing attention in few-shot
learning because they can provide a new paradigm for transferable visual
representation learning with easily available text on the Web. However, the
VLPs may neglect detailed visual information that is difficult to describe by
language sentences, but important for learning an effective classifier to
distinguish different images. To address the above problem, we propose a new
framework, named Semantic-guided Visual Adapting (SgVA), which can effectively
extend vision-language pre-trained models to produce discriminative adapted
visual features by comprehensively using an implicit knowledge distillation, a
vision-specific contrastive loss, and a cross-modal contrastive loss. The
implicit knowledge distillation is designed to transfer the fine-grained
cross-modal knowledge to guide the updating of the vision adapter.
State-of-the-art results on 13 datasets demonstrate that the adapted visual
features can well complement the cross-modal features to improve few-shot image
classification.