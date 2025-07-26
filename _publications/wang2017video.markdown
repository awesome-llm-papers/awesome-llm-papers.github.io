---
layout: publication
title: Video Captioning Via Hierarchical Reinforcement Learning
authors: Xin Wang, Wenhu Chen, Jiawei Wu, Yuan-fang Wang, William Yang Wang
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2018
bibkey: wang2017video
citations: 269
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.11135'}]
tags: ["CVPR", "Reinforcement Learning"]
short_authors: Wang et al.
---
Video captioning is the task of automatically generating a textual
description of the actions in a video. Although previous work (e.g.
sequence-to-sequence model) has shown promising results in abstracting a coarse
description of a short video, it is still very challenging to caption a video
containing multiple fine-grained actions with a detailed description. This
paper aims to address the challenge by proposing a novel hierarchical
reinforcement learning framework for video captioning, where a high-level
Manager module learns to design sub-goals and a low-level Worker module
recognizes the primitive actions to fulfill the sub-goal. With this
compositional framework to reinforce video captioning at different levels, our
approach significantly outperforms all the baseline methods on a newly
introduced large-scale dataset for fine-grained video captioning. Furthermore,
our non-ensemble model has already achieved the state-of-the-art results on the
widely-used MSR-VTT dataset.