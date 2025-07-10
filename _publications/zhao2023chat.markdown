---
layout: publication
title: 'Chat With The Environment: Interactive Multimodal Perception Using Large Language
  Models'
authors: Xufeng Zhao, Mengdi Li, Cornelius Weber, Muhammad Burhan Hafez, Stefan Wermter
conference: 2023 IEEE/RSJ International Conference on Intelligent Robots and Systems
  (IROS)
year: 2023
citations: 26
bibkey: zhao2023chat
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.08268'}]
tags: [Few-Shot, Tools, Reinforcement Learning, Multimodal Models, Agentic]
---
Programming robot behavior in a complex world faces challenges on multiple
levels, from dextrous low-level skills to high-level planning and reasoning.
Recent pre-trained Large Language Models (LLMs) have shown remarkable reasoning
ability in few-shot robotic planning. However, it remains challenging to ground
LLMs in multimodal sensory input and continuous action output, while enabling a
robot to interact with its environment and acquire novel information as its
policies unfold. We develop a robot interaction scenario with a partially
observable state, which necessitates a robot to decide on a range of epistemic
actions in order to sample sensory information among multiple modalities,
before being able to execute the task correctly. Matcha (Multimodal environment
chatting) agent, an interactive perception framework, is therefore proposed
with an LLM as its backbone, whose ability is exploited to instruct epistemic
actions and to reason over the resulting multimodal sensations (vision, sound,
haptics, proprioception), as well as to plan an entire task execution based on
the interactively acquired information. Our study demonstrates that LLMs can
provide high-level planning and reasoning skills and control interactive robot
behavior in a multimodal environment, while multimodal modules with the context
of the environmental state help ground the LLMs and extend their processing
ability. The project website can be found at https://matcha-agent.github.io.