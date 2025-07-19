---
layout: publication
title: 'Hindsight Planner: A Closed-loop Few-shot Planner For Embodied Instruction
  Following'
authors: Yang et al.
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2024
bibkey: yang2024hindsight
citations: 155
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.19562'}]
tags: [ICCV, Agentic, Few Shot, Security, Datasets]
---
This work focuses on building a task planner for Embodied Instruction
Following (EIF) using Large Language Models (LLMs). Previous works typically
train a planner to imitate expert trajectories, treating this as a supervised
task. While these methods achieve competitive performance, they often lack
sufficient robustness. When a suboptimal action is taken, the planner may
encounter an out-of-distribution state, which can lead to task failure. In
contrast, we frame the task as a Partially Observable Markov Decision Process
(POMDP) and aim to develop a robust planner under a few-shot assumption. Thus,
we propose a closed-loop planner with an adaptation module and a novel
hindsight method, aiming to use as much information as possible to assist the
planner. Our experiments on the ALFRED dataset indicate that our planner
achieves competitive performance under a few-shot assumption. For the first
time, our few-shot agent's performance approaches and even surpasses that of
the full-shot supervised agent.