---
layout: publication
title: Scene Memory Transformer For Embodied Agents In Long-horizon Tasks
authors: Kuan Fang, Alexander Toshev, Li Fei-fei, Silvio Savarese
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2019
bibkey: fang2019scene
citations: 169
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1903.03878'}]
tags: ["Agentic", "CVPR", "Model Architecture"]
short_authors: Fang et al.
---
Many robotic applications require the agent to perform long-horizon tasks in
partially observable environments. In such applications, decision making at any
step can depend on observations received far in the past. Hence, being able to
properly memorize and utilize the long-term history is crucial. In this work,
we propose a novel memory-based policy, named Scene Memory Transformer (SMT).
The proposed policy embeds and adds each observation to a memory and uses the
attention mechanism to exploit spatio-temporal dependencies. This model is
generic and can be efficiently trained with reinforcement learning over long
episodes. On a range of visual navigation tasks, SMT demonstrates superior
performance to existing reactive and memory-based policies by a margin.