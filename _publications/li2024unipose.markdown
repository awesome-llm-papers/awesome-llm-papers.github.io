---
layout: publication
title: 'Unipose: A Unified Multimodal Framework For Human Pose Comprehension, Generation
  And Editing'
authors: Li et al.
conference: 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: li2024unipose
citations: 139
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.16781'}]
tags: [Multimodal Models, Tools, CVPR, Reinforcement Learning]
---
Human pose plays a crucial role in the digital age. While recent works have
achieved impressive progress in understanding and generating human poses, they
often support only a single modality of control signals and operate in
isolation, limiting their application in real-world scenarios. This paper
presents UniPose, a framework employing Large Language Models (LLMs) to
comprehend, generate, and edit human poses across various modalities, including
images, text, and 3D SMPL poses. Specifically, we apply a pose tokenizer to
convert 3D poses into discrete pose tokens, enabling seamless integration into
the LLM within a unified vocabulary. To further enhance the fine-grained pose
perception capabilities, we facilitate UniPose with a mixture of visual
encoders, among them a pose-specific visual encoder. Benefiting from a unified
learning strategy, UniPose effectively transfers knowledge across different
pose-relevant tasks, adapts to unseen tasks, and exhibits extended
capabilities. This work serves as the first attempt at building a
general-purpose framework for pose comprehension, generation, and editing.
Extensive experiments highlight UniPose's competitive and even superior
performance across various pose-relevant tasks.