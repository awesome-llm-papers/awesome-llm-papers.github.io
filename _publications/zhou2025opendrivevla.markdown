---
layout: publication
title: 'Opendrivevla: Towards End-to-end Autonomous Driving With Large Vision Language
  Action Model'
authors: Zhou et al.
conference: IEEE Robotics and Automation Letters
year: 2025
bibkey: zhou2025opendrivevla
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.23463'}]
tags: [Multimodal Models, Agentic, Datasets, GPT]
---
We present OpenDriveVLA, a Vision-Language Action (VLA) model designed for
end-to-end autonomous driving. OpenDriveVLA builds upon open-source pre-trained
large Vision-Language Models (VLMs) to generate reliable driving actions,
conditioned on 3D environmental perception, ego vehicle states, and driver
commands. To bridge the modality gap between driving visual representations and
language embeddings, we propose a hierarchical vision-language alignment
process, projecting both 2D and 3D structured visual tokens into a unified
semantic space. Besides, OpenDriveVLA models the dynamic relationships between
the ego vehicle, surrounding agents, and static road elements through an
autoregressive agent-env-ego interaction process, ensuring both spatially and
behaviorally informed trajectory planning. Extensive experiments on the
nuScenes dataset demonstrate that OpenDriveVLA achieves state-of-the-art
results across open-loop trajectory planning and driving-related
question-answering tasks. Qualitative analyses further illustrate
OpenDriveVLA's superior capability to follow high-level driving commands and
robustly generate trajectories under challenging scenarios, highlighting its
potential for next-generation end-to-end autonomous driving. We will release
our code to facilitate further research in this domain.