---
layout: publication
title: 'All In One: Exploring Unified Video-language Pre-training'
authors: Alex Jinpeng Wang, Yixiao Ge, Rui Yan, Yuying Ge, Xudong Lin, Guanyu Cai,
  Jianping Wu, Ying Shan, Xiaohu Qie, Mike Zheng Shou
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: wang2022all
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.07303'}]
tags: ["CVPR"]
short_authors: Wang et al.
---
Mainstream Video-Language Pre-training models \cite\{actbert,clipbert,violet\}
consist of three parts, a video encoder, a text encoder, and a video-text
fusion Transformer. They pursue better performance via utilizing heavier
unimodal encoders or multimodal fusion Transformers, resulting in increased
parameters with lower efficiency in downstream tasks. In this work, we for the
first time introduce an end-to-end video-language model, namely
\textit\{all-in-one Transformer\}, that embeds raw video and textual signals into
joint representations using a unified backbone architecture. We argue that the
unique temporal information of video data turns out to be a key barrier
hindering the design of a modality-agnostic Transformer. To overcome the
challenge, we introduce a novel and effective token rolling operation to encode
temporal representations from video clips in a non-parametric manner. The
careful design enables the representation learning of both video-text
multimodal inputs and unimodal inputs using a unified backbone model. Our
pre-trained all-in-one Transformer is transferred to various downstream
video-text tasks after fine-tuning, including text-video retrieval,
video-question answering, multiple choice and visual commonsense reasoning.
State-of-the-art performances with the minimal model FLOPs on nine datasets
demonstrate the superiority of our method compared to the competitive
counterparts. The code and pretrained model have been released in
https://github.com/showlab/all-in-one.