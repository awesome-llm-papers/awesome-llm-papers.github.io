---
layout: publication
title: Multi-view Multi-behavior Contrastive Learning In Recommendation
authors: Wu et al.
conference: Lecture Notes in Computer Science
year: 2022
bibkey: wu2022multi
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.10576'}]
tags: [Reinforcement Learning, Tools, Evaluation, Datasets]
---
Multi-behavior recommendation (MBR) aims to jointly consider multiple
behaviors to improve the target behavior's performance. We argue that MBR
models should: (1) model the coarse-grained commonalities between different
behaviors of a user, (2) consider both individual sequence view and global
graph view in multi-behavior modeling, and (3) capture the fine-grained
differences between multiple behaviors of a user. In this work, we propose a
novel Multi-behavior Multi-view Contrastive Learning Recommendation (MMCLR)
framework, including three new CL tasks to solve the above challenges,
respectively. The multi-behavior CL aims to make different user single-behavior
representations of the same user in each view to be similar. The multi-view CL
attempts to bridge the gap between a user's sequence-view and graph-view
representations. The behavior distinction CL focuses on modeling fine-grained
differences of different behaviors. In experiments, we conduct extensive
evaluations and ablation tests to verify the effectiveness of MMCLR and various
CL tasks on two real-world datasets, achieving SOTA performance over existing
baselines. Our code will be available on
https://github.com/wyqing20/MMCLR