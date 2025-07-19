---
layout: publication
title: 'Unitable: Towards A Unified Framework For Table Recognition Via Self-supervised
  Pretraining'
authors: Peng et al.
conference: 2022 IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)
year: 2024
bibkey: peng2024unitable
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.04822'}]
tags: [Training Techniques, GPT, Tools, Model Architecture, Language Modeling, Reinforcement
    Learning, Applications, Multimodal Models, Datasets]
---
Tables convey factual and quantitative data with implicit conventions created
by humans that are often challenging for machines to parse. Prior work on table
recognition (TR) has mainly centered around complex task-specific combinations
of available inputs and tools. We present UniTable, a training framework that
unifies both the training paradigm and training objective of TR. Its training
paradigm combines the simplicity of purely pixel-level inputs with the
effectiveness and scalability empowered by self-supervised pretraining from
diverse unannotated tabular images. Our framework unifies the training
objectives of all three TR tasks - extracting table structure, cell content,
and cell bounding box - into a unified task-agnostic training objective:
language modeling. Extensive quantitative and qualitative analyses highlight
UniTable's state-of-the-art (SOTA) performance on four of the largest TR
datasets. UniTable's table parsing capability has surpassed both existing TR
methods and general large vision-language models, e.g., GPT-4o, GPT-4-turbo
with vision, and LLaVA. Our code is publicly available at
https://github.com/poloclub/unitable, featuring a Jupyter Notebook that
includes the complete inference pipeline, fine-tuned across multiple TR
datasets, supporting all three TR tasks.