---
layout: publication
title: 'T2m-hifigpt: Generating High Quality Human Motion From Textual Descriptions
  With Residual Discrete Representations'
authors: Wang Congyi
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: wang2023t2m
citations: 120
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.10628'}]
tags: [GPT, Prompting, Tools, CVPR, Ethics And Bias, Transformer, Evaluation, Model
    Architecture, Reinforcement Learning, Datasets, Merging]
---
In this study, we introduce T2M-HiFiGPT, a novel conditional generative
framework for synthesizing human motion from textual descriptions. This
framework is underpinned by a Residual Vector Quantized Variational AutoEncoder
(RVQ-VAE) and a double-tier Generative Pretrained Transformer (GPT)
architecture. We demonstrate that our CNN-based RVQ-VAE is capable of producing
highly accurate 2D temporal-residual discrete motion representations. Our
proposed double-tier GPT structure comprises a temporal GPT and a residual GPT.
The temporal GPT efficiently condenses information from previous frames and
textual descriptions into a 1D context vector. This vector then serves as a
context prompt for the residual GPT, which generates the final residual
discrete indices. These indices are subsequently transformed back into motion
data by the RVQ-VAE decoder. To mitigate the exposure bias issue, we employ
straightforward code corruption techniques for RVQ and a conditional dropout
strategy, resulting in enhanced synthesis performance. Remarkably, T2M-HiFiGPT
not only simplifies the generative process but also surpasses existing methods
in both performance and parameter efficacy, including the latest
diffusion-based and GPT-based models. On the HumanML3D and KIT-ML datasets, our
framework achieves exceptional results across nearly all primary metrics. We
further validate the efficacy of our framework through comprehensive ablation
studies on the HumanML3D dataset, examining the contribution of each component.
Our findings reveal that RVQ-VAE is more adept at capturing precise 3D human
motion with comparable computational demand compared to its VQ-VAE
counterparts. As a result, T2M-HiFiGPT enables the generation of human motion
with significantly increased accuracy, outperforming recent state-of-the-art
approaches such as T2M-GPT and Att-T2M.