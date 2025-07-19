---
layout: publication
title: 'Fewer Tokens And Fewer Videos: Extending Video Understanding Abilities In
  Large Vision-language Models'
authors: Chen et al.
conference: 'Proceedings of the 62nd Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2024
bibkey: chen2024fewer
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.08024'}]
tags: [Model Architecture, Training Techniques, Evaluation, ACL, RAG, Multimodal Models,
  Datasets]
---
Amidst the advancements in image-based Large Vision-Language Models
(image-LVLM), the transition to video-based models (video-LVLM) is hindered by
the limited availability of quality video data. This paper addresses the
challenge by leveraging the visual commonalities between images and videos to
efficiently evolve image-LVLMs into video-LVLMs. We present a cost-effective
video-LVLM that enhances model architecture, introduces innovative training
strategies, and identifies the most effective types of video instruction data.
Our innovative weighted token sampler significantly compresses the visual token
numbers of each video frame, effectively cutting computational expenses. We
also find that judiciously using just 10% of the video data, compared to prior
video-LVLMs, yields impressive results during various training phases.
Moreover, we delve into the influence of video instruction data in
limited-resource settings, highlighting the significance of incorporating video
training data that emphasizes temporal understanding to enhance model
performance. The resulting Fewer Tokens and Fewer Videos LVLM (FTFV-LVLM)
exhibits exceptional performance across video and image benchmarks, validating
our model's design and training approaches.