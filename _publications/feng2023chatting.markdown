---
layout: publication
title: 'Chatpose: Chatting About 3D Human Pose'
authors: Yao Feng et al.
conference: 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
citations: 15
bibkey: feng2023chatting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.18836'}]
tags: [RAG, Tools, Reinforcement Learning, Multimodal Models, Evaluation]
---
We introduce ChatPose, a framework employing Large Language Models (LLMs) to
understand and reason about 3D human poses from images or textual descriptions.
Our work is motivated by the human ability to intuitively understand postures
from a single image or a brief description, a process that intertwines image
interpretation, world knowledge, and an understanding of body language.
Traditional human pose estimation and generation methods often operate in
isolation, lacking semantic understanding and reasoning abilities. ChatPose
addresses these limitations by embedding SMPL poses as distinct signal tokens
within a multimodal LLM, enabling the direct generation of 3D body poses from
both textual and visual inputs. Leveraging the powerful capabilities of
multimodal LLMs, ChatPose unifies classical 3D human pose and generation tasks
while offering user interactions. Additionally, ChatPose empowers LLMs to apply
their extensive world knowledge in reasoning about human poses, leading to two
advanced tasks: speculative pose generation and reasoning about pose
estimation. These tasks involve reasoning about humans to generate 3D poses
from subtle text queries, possibly accompanied by images. We establish
benchmarks for these tasks, moving beyond traditional 3D pose generation and
estimation methods. Our results show that ChatPose outperforms existing
multimodal LLMs and task-specific methods on these newly proposed tasks.
Furthermore, ChatPose's ability to understand and generate 3D human poses based
on complex reasoning opens new directions in human pose analysis.