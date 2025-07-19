---
layout: publication
title: 'VLA-3D: A Dataset For 3D Semantic Scene Understanding And Navigation'
authors: Zhang et al.
conference: The International Journal of Robotics Research
year: 2024
bibkey: zhang2024vla
citations: 99
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.03540'}]
tags: [Agentic, Evaluation, Reinforcement Learning, Security, Multimodal Models, Datasets]
---
With the recent rise of Large Language Models (LLMs), Vision-Language Models
(VLMs), and other general foundation models, there is growing potential for
multimodal, multi-task embodied agents that can operate in diverse environments
given only natural language as input. One such application area is indoor
navigation using natural language instructions. However, despite recent
progress, this problem remains challenging due to the spatial reasoning and
semantic understanding required, particularly in arbitrary scenes that may
contain many objects belonging to fine-grained classes. To address this
challenge, we curate the largest real-world dataset for Vision and
Language-guided Action in 3D Scenes (VLA-3D), consisting of over 11.5K scanned
3D indoor rooms from existing datasets, 23.5M heuristically generated semantic
relations between objects, and 9.7M synthetically generated referential
statements. Our dataset consists of processed 3D point clouds, semantic object
and room annotations, scene graphs, navigable free space annotations, and
referential language statements that specifically focus on view-independent
spatial relations for disambiguating objects. The goal of these features is to
aid the downstream task of navigation, especially on real-world systems where
some level of robustness must be guaranteed in an open world of changing scenes
and imperfect language. We benchmark our dataset with current state-of-the-art
models to obtain a performance baseline. All code to generate and visualize the
dataset is publicly released, see https://github.com/HaochenZ11/VLA-3D. With
the release of this dataset, we hope to provide a resource for progress in
semantic 3D scene understanding that is robust to changes and one which will
aid the development of interactive indoor navigation systems.