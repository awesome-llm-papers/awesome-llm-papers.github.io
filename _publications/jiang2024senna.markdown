---
layout: publication
title: 'Senna: Bridging Large Vision-language Models And End-to-end Autonomous Driving'
authors: Jiang et al.
conference: Journal of Systems Architecture
year: 2024
bibkey: jiang2024senna
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.22313'}]
tags: [RAG, Training Techniques, Prompting, Model Architecture, Fine Tuning, Multimodal
    Models, Datasets, Merging]
---
End-to-end autonomous driving demonstrates strong planning capabilities with
large-scale data but still struggles in complex, rare scenarios due to limited
commonsense. In contrast, Large Vision-Language Models (LVLMs) excel in scene
understanding and reasoning. The path forward lies in merging the strengths of
both approaches. Previous methods using LVLMs to predict trajectories or
control signals yield suboptimal results, as LVLMs are not well-suited for
precise numerical predictions. This paper presents Senna, an autonomous driving
system combining an LVLM (Senna-VLM) with an end-to-end model (Senna-E2E).
Senna decouples high-level planning from low-level trajectory prediction.
Senna-VLM generates planning decisions in natural language, while Senna-E2E
predicts precise trajectories. Senna-VLM utilizes a multi-image encoding
approach and multi-view prompts for efficient scene understanding. Besides, we
introduce planning-oriented QAs alongside a three-stage training strategy,
which enhances Senna-VLM's planning performance while preserving commonsense.
Extensive experiments on two datasets show that Senna achieves state-of-the-art
planning performance. Notably, with pre-training on a large-scale dataset
DriveX and fine-tuning on nuScenes, Senna significantly reduces average
planning error by 27.12% and collision rate by 33.33% over model without
pre-training. We believe Senna's cross-scenario generalization and
transferability are essential for achieving fully autonomous driving. Code and
models will be released at https://github.com/hustvl/Senna.