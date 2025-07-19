---
layout: publication
title: Temporal Preference Optimization For Long-form Video Understanding
authors: Li et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: li2025temporal
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.13919'}]
tags: [RAG, Training Techniques, Tools, CVPR, Evaluation, Efficiency And Optimization,
  Reinforcement Learning, Multimodal Models, Datasets]
---
Despite significant advancements in video large multimodal models
(video-LMMs), achieving effective temporal grounding in long-form videos
remains a challenge for existing models. To address this limitation, we propose
Temporal Preference Optimization (TPO), a novel post-training framework
designed to enhance the temporal grounding capabilities of video-LMMs through
preference learning. TPO adopts a self-training approach that enables models to
differentiate between well-grounded and less accurate temporal responses by
leveraging curated preference datasets at two granularities: localized temporal
grounding, which focuses on specific video segments, and comprehensive temporal
grounding, which captures extended temporal dependencies across entire video
sequences. By optimizing on these preference datasets, TPO significantly
enhances temporal understanding while reducing reliance on manually annotated
data. Extensive experiments on three long-form video understanding
benchmarks--LongVideoBench, MLVU, and Video-MME--demonstrate the effectiveness
of TPO across two state-of-the-art video-LMMs. Notably, LLaVA-Video-TPO
establishes itself as the leading 7B model on the Video-MME benchmark,
underscoring the potential of TPO as a scalable and efficient solution for
advancing temporal reasoning in long-form video understanding. Project page:
https://ruili33.github.io/tpo_website.