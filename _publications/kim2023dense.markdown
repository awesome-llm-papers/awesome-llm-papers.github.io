---
layout: publication
title: Dense Text-to-image Generation With Attention Modulation
authors: Kim et al.
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2023
bibkey: kim2023dense
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.12964'}]
tags: [ICCV, Training Techniques, Attention Mechanism, Prompting, Evaluation, Model
    Architecture, Fine Tuning, Datasets, Merging]
---
Existing text-to-image diffusion models struggle to synthesize realistic
images given dense captions, where each text prompt provides a detailed
description for a specific image region. To address this, we propose
DenseDiffusion, a training-free method that adapts a pre-trained text-to-image
model to handle such dense captions while offering control over the scene
layout. We first analyze the relationship between generated images' layouts and
the pre-trained model's intermediate attention maps. Next, we develop an
attention modulation method that guides objects to appear in specific regions
according to layout guidance. Without requiring additional fine-tuning or
datasets, we improve image generation performance given dense captions
regarding both automatic and human evaluation scores. In addition, we achieve
similar-quality visual results with models specifically trained with layout
conditions.