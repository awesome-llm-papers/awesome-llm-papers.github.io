---
layout: publication
title: 'Minedreamer: Learning To Follow Instructions Via Chain-of-imagination For
  Simulated-world Control'
authors: Zhou et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: zhou2024minedreamer
citations: 620
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.12037'}]
tags: [Prompting, Agentic, CVPR, Reinforcement Learning, Multimodal Models, Merging]
---
It is a long-lasting goal to design a generalist-embodied agent that can
follow diverse instructions in human-like ways. However, existing approaches
often fail to steadily follow instructions due to difficulties in understanding
abstract and sequential natural language instructions. To this end, we
introduce MineDreamer, an open-ended embodied agent built upon the challenging
Minecraft simulator with an innovative paradigm that enhances
instruction-following ability in low-level control signal generation.
Specifically, MineDreamer is developed on top of recent advances in Multimodal
Large Language Models (MLLMs) and diffusion models, and we employ a
Chain-of-Imagination (CoI) mechanism to envision the step-by-step process of
executing instructions and translating imaginations into more precise visual
prompts tailored to the current state; subsequently, the agent generates
keyboard-and-mouse actions to efficiently achieve these imaginations, steadily
following the instructions at each step. Extensive experiments demonstrate that
MineDreamer follows single and multi-step instructions steadily, significantly
outperforming the best generalist agent baseline and nearly doubling its
performance. Moreover, qualitative analysis of the agent's imaginative ability
reveals its generalization and comprehension of the open world.