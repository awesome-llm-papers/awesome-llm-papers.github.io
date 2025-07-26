---
layout: publication
title: Frozen CLIP Models Are Efficient Video Learners
authors: Ziyi Lin, Shijie Geng, Renrui Zhang, Peng Gao, Gerard de Melo, Xiaogang Wang,
  Jifeng Dai, Yu Qiao, Hongsheng Li
conference: Lecture Notes in Computer Science
year: 2022
bibkey: lin2022frozen
citations: 106
additional_links: [{name: Code, url: 'https://github.com/OpenGVLab/efficient-video-recognition'},
  {name: Paper, url: 'https://arxiv.org/abs/2208.03550'}]
tags: ["Model Architecture"]
short_authors: Lin et al.
---
Video recognition has been dominated by the end-to-end learning paradigm --
first initializing a video recognition model with weights of a pretrained image
model and then conducting end-to-end training on videos. This enables the video
network to benefit from the pretrained image model. However, this requires
substantial computation and memory resources for finetuning on videos and the
alternative of directly using pretrained image features without finetuning the
image backbone leads to subpar results. Fortunately, recent advances in
Contrastive Vision-Language Pre-training (CLIP) pave the way for a new route
for visual recognition tasks. Pretrained on large open-vocabulary image-text
pair data, these models learn powerful visual representations with rich
semantics. In this paper, we present Efficient Video Learning (EVL) -- an
efficient framework for directly training high-quality video recognition models
with frozen CLIP features. Specifically, we employ a lightweight Transformer
decoder and learn a query token to dynamically collect frame-level spatial
features from the CLIP image encoder. Furthermore, we adopt a local temporal
module in each decoder layer to discover temporal clues from adjacent frames
and their attention maps. We show that despite being efficient to train with a
frozen backbone, our models learn high quality video representations on a
variety of video recognition datasets. Code is available at
https://github.com/OpenGVLab/efficient-video-recognition.