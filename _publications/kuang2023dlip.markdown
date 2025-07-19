---
layout: publication
title: 'DLIP: Distilling Language-image Pre-training'
authors: Kuang et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: kuang2023dlip
citations: 520
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.12956'}]
tags: [Training Techniques, Distillation, Tools, CVPR, Model Architecture, Efficiency
    And Optimization, Applications, Multimodal Models, Quantization]
---
Vision-Language Pre-training (VLP) shows remarkable progress with the
assistance of extremely heavy parameters, which challenges deployment in real
applications. Knowledge distillation is well recognized as the essential
procedure in model compression. However, existing knowledge distillation
techniques lack an in-depth investigation and analysis of VLP, and practical
guidelines for VLP-oriented distillation are still not yet explored. In this
paper, we present DLIP, a simple yet efficient Distilling Language-Image
Pre-training framework, through which we investigate how to distill a light VLP
model. Specifically, we dissect the model distillation from multiple
dimensions, such as the architecture characteristics of different modules and
the information transfer of different modalities. We conduct comprehensive
experiments and provide insights on distilling a light but performant VLP
model. Experimental results reveal that DLIP can achieve a state-of-the-art
accuracy/efficiency trade-off across diverse cross-modal tasks, e.g.,
image-text retrieval, image captioning and visual question answering. For
example, DLIP compresses BLIP by 1.9x, from 213M to 108M parameters, while
achieving comparable or better performance. Furthermore, DLIP succeeds in
retaining more than 95% of the performance with 22.4% parameters and 24.8%
FLOPs compared to the teacher model and accelerates inference speed by 2.7x.