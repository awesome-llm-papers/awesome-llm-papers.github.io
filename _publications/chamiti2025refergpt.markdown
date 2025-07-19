---
layout: publication
title: 'Refergpt: Towards Zero-shot Referring Multi-object Tracking'
authors: Chamiti et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: chamiti2025refergpt
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.09195'}]
tags: [RAG, Training Techniques, GPT, Tools, CVPR, Model Architecture, Reinforcement
    Learning, Security]
---
Tracking multiple objects based on textual queries is a challenging task that
requires linking language understanding with object association across frames.
Previous works typically train the whole process end-to-end or integrate an
additional referring text module into a multi-object tracker, but they both
require supervised training and potentially struggle with generalization to
open-set queries. In this work, we introduce ReferGPT, a novel zero-shot
referring multi-object tracking framework. We provide a multi-modal large
language model (MLLM) with spatial knowledge enabling it to generate 3D-aware
captions. This enhances its descriptive capabilities and supports a more
flexible referring vocabulary without training. We also propose a robust
query-matching strategy, leveraging CLIP-based semantic encoding and fuzzy
matching to associate MLLM generated captions with user queries. Extensive
experiments on Refer-KITTI, Refer-KITTIv2 and Refer-KITTI+ demonstrate that
ReferGPT achieves competitive performance against trained methods, showcasing
its robustness and zero-shot capabilities in autonomous driving. The codes are
available on https://github.com/Tzoulio/ReferGPT