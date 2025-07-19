---
layout: publication
title: 'Reason3d: Searching And Reasoning 3D Segmentation Via Large Language Model'
authors: Huang et al.
conference: 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: huang2024reason3d
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.17427'}]
tags: [Prompting, CVPR, Reinforcement Learning, Applications, Multimodal Models, Datasets]
---
Recent advancements in multimodal large language models (LLMs) have
demonstrated significant potential across various domains, particularly in
concept reasoning. However, their applications in understanding 3D environments
remain limited, primarily offering textual or numerical outputs without
generating dense, informative segmentation masks. This paper introduces
Reason3D, a novel LLM designed for comprehensive 3D understanding. Reason3D
processes point cloud data and text prompts to produce textual responses and
segmentation masks, enabling advanced tasks such as 3D reasoning segmentation,
hierarchical searching, express referring, and question answering with detailed
mask outputs. We propose a hierarchical mask decoder that employs a
coarse-to-fine approach to segment objects within expansive scenes. It begins
with a coarse location estimation, followed by object mask estimation, using
two unique tokens predicted by LLMs based on the textual query. Experimental
results on large-scale ScanNet and Matterport3D datasets validate the
effectiveness of our Reason3D across various tasks.