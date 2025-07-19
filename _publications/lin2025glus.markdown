---
layout: publication
title: 'GLUS: Global-local Reasoning Unified Into A Single Large Language Model For
  Video Segmentation'
authors: Lin et al.
conference: 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: lin2025glus
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.07962'}]
tags: [Training Techniques, Tools, CVPR, Evaluation, Efficiency And Optimization,
  Reinforcement Learning, Datasets]
---
This paper proposes a novel framework utilizing multi-modal large language
models (MLLMs) for referring video object segmentation (RefVOS). Previous
MLLM-based methods commonly struggle with the dilemma between "Ref" and "VOS":
they either specialize in understanding a few key frames (global reasoning) or
tracking objects on continuous frames (local reasoning), and rely on external
VOS or frame selectors to mitigate the other end of the challenge. However, our
framework GLUS shows that global and local consistency can be unified into a
single video segmentation MLLM: a set of sparse "context frames" provides
global information, while a stream of continuous "query frames" conducts local
object tracking. This is further supported by jointly training the MLLM with a
pre-trained VOS memory bank to simultaneously digest short-range and long-range
temporal information. To improve the information efficiency within the limited
context window of MLLMs, we introduce object contrastive learning to
distinguish hard false-positive objects and a self-refined framework to
identify crucial frames and perform propagation. By collectively integrating
these insights, our GLUS delivers a simple yet effective baseline, achieving
new state-of-the-art for MLLMs on the MeViS and Ref-Youtube-VOS benchmark. Our
project page is at https://glus-video.github.io/.