---
layout: publication
title: 'Roco: Dialectic Multi-robot Collaboration With Large Language Models'
authors: Zhao Mandi, Shreeya Jain, Shuran Song
conference: Arxiv
year: 2023
citations: 30
bibkey: mandi2023dialectic
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.04738'}, {name: Code,
    url: 'https://project-roco.github.io'}]
tags: [Reinforcement Learning, Interpretability and Explainability, Agentic, Has Code,
  Prompting]
---
We propose a novel approach to multi-robot collaboration that harnesses the
power of pre-trained large language models (LLMs) for both high-level
communication and low-level path planning. Robots are equipped with LLMs to
discuss and collectively reason task strategies. They then generate sub-task
plans and task space waypoint paths, which are used by a multi-arm motion
planner to accelerate trajectory planning. We also provide feedback from the
environment, such as collision checking, and prompt the LLM agents to improve
their plan and waypoints in-context. For evaluation, we introduce RoCoBench, a
6-task benchmark covering a wide range of multi-robot collaboration scenarios,
accompanied by a text-only dataset for agent representation and reasoning. We
experimentally demonstrate the effectiveness of our approach -- it achieves
high success rates across all tasks in RoCoBench and adapts to variations in
task semantics. Our dialog setup offers high interpretability and flexibility
-- in real world experiments, we show RoCo easily incorporates
human-in-the-loop, where a user can communicate and collaborate with a robot
agent to complete tasks together. See project website
https://project-roco.github.io for videos and code.