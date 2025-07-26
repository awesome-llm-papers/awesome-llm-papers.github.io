---
layout: publication
title: 'WALL-E: World Alignment By Rule Learning Improves World Model-based LLM Agents'
authors: Siyu Zhou, Tianyi Zhou, Yijun Yang, Guodong Long, Deheng Ye, Jing Jiang,
  Chengqi Zhang
conference: No Venue
year: 2024
bibkey: zhou2024wall
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2410.07484'}]
tags: ["Agentic", "Efficiency"]
short_authors: Zhou et al.
---
Can large language models (LLMs) directly serve as powerful world models for model-based agents? While the gaps between the prior knowledge of LLMs and the specified environment's dynamics do exist, our study reveals that the gaps can be bridged by aligning an LLM with its deployed environment and such "world alignment" can be efficiently achieved by rule learning on LLMs. Given the rich prior knowledge of LLMs, only a few additional rules suffice to align LLM predictions with the specified environment dynamics. To this end, we propose a neurosymbolic approach to learn these rules gradient-free through LLMs, by inducing, updating, and pruning rules based on comparisons of agent-explored trajectories and world model predictions. The resulting world model is composed of the LLM and the learned rules. Our embodied LLM agent "WALL-E" is built upon model-predictive control (MPC). By optimizing look-ahead actions based on the precise world model, MPC significantly improves exploration and learning efficiency. Compared to existing LLM agents, WALL-E's reasoning only requires a few principal rules rather than verbose buffered trajectories being included in the LLM input. On open-world challenges in Minecraft and ALFWorld, WALL-E achieves higher success rates than existing methods, with lower costs on replanning time and the number of tokens used for reasoning. In Minecraft, WALL-E exceeds baselines by 15-30% in success rate while costing 8-20 fewer replanning rounds and only 60-80% of tokens. In ALFWorld, its success rate surges to a new record high of 95% only after 6 iterations.

https://huggingface.co/discussions/paper/670906452f30a8b4755bfd7b