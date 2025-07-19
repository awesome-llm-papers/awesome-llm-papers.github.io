---
layout: publication
title: 'Villa: Video Reasoning Segmentation With Large Language Model'
authors: Zheng et al.
conference: 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: zheng2024villa
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.14500'}]
tags: [Tools, Evaluation, CVPR, Reinforcement Learning, Multimodal Models, Datasets]
---
Recent efforts in video reasoning segmentation (VRS) integrate large language
models (LLMs) with perception models to localize and track objects via textual
instructions, achieving barely satisfactory results in simple scenarios.
However, they struggled to discriminate and deduce the objects from user
queries in more real-world scenes featured by long durations, multiple objects,
rapid motion, and heavy occlusions. In this work, we analyze the underlying
causes of these limitations, and present ViLLa: Video reasoning segmentation
with Large Language Model. Remarkably, our ViLLa manages to tackle these
challenges through multiple core innovations: (1) a context synthesizer that
dynamically encodes the user intent with video contexts for accurate reasoning,
resolving ambiguities in complex queries, and (2) a hierarchical temporal
synchronizer that disentangles multi-object interactions across complex
temporal scenarios by modelling multi-object interactions at local and global
temporal scales. To enable efficient processing of long videos, ViLLa
incorporates (3) a key segment sampler that adaptively partitions long videos
into shorter but semantically dense segments for less redundancy. What's more,
to promote research in this unexplored area, we construct a VRS benchmark,
VideoReasonSeg, featuring different complex scenarios. Our model also exhibits
impressive state-of-the-art results on VideoReasonSeg, Ref-YouTube-VOS,
Ref-DAVIS17, MeViS, and ReVOS. Both quantitative and qualitative experiments
demonstrate that our method effectively enhances video reasoning segmentation
capabilities for multimodal LLMs. The code and dataset will be available at
https://github.com/rkzheng99/ViLLa.