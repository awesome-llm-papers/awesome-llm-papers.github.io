---
layout: publication
title: 'Openmaskdino3d : Reasoning 3D Segmentation Via Large Language Model'
authors: Zhang Kunshen
conference: 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: zhang2025openmaskdino3d
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.04837'}]
tags: [Alt, Prompting, Tools, CVPR, Reinforcement Learning, Datasets]
---
Although perception systems have made remarkable advancements in recent years, particularly in 2D reasoning segmentation, these systems still rely on explicit human instruction or pre-defined categories to identify target objects before executing visual recognition tasks. Such systems have matured significantly, demonstrating the ability to reason and comprehend implicit user intentions in two-dimensional contexts, producing accurate segmentation masks based on complex and implicit query text. However, a comparable framework and structure for 3D reasoning segmentation remain absent. This paper introduces OpenMaskDINO3D, a LLM designed for comprehensive 3D understanding and segmentation. OpenMaskDINO3D processes point cloud data and text prompts to produce instance segmentation masks, excelling in many 3D tasks. By introducing a SEG token and object identifier, we achieve high-precision 3D segmentation mask generation, enabling the model to directly produce accurate point cloud segmentation results from natural language instructions. Experimental results on large-scale ScanNet datasets validate the effectiveness of our OpenMaskDINO3D across various tasks.