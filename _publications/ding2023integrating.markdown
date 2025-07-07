---
layout: publication
title: Integrating Action Knowledge And Llms For Task Planning And Situation Handling
  In Open Worlds
authors: Yan Ding et al.
conference: Autonomous Robots 2023
year: 2023
citations: 21
bibkey: ding2023integrating
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.17590'}]
tags: [RAG, Tools, Reinforcement Learning]
---
Task planning systems have been developed to help robots use human knowledge
(about actions) to complete long-horizon tasks. Most of them have been
developed for "closed worlds" while assuming the robot is provided with
complete world knowledge. However, the real world is generally open, and the
robots frequently encounter unforeseen situations that can potentially break
the planner's completeness. Could we leverage the recent advances on
pre-trained Large Language Models (LLMs) to enable classical planning systems
to deal with novel situations?
  This paper introduces a novel framework, called COWP, for open-world task
planning and situation handling. COWP dynamically augments the robot's action
knowledge, including the preconditions and effects of actions, with
task-oriented commonsense knowledge. COWP embraces the openness from LLMs, and
is grounded to specific domains via action knowledge. For systematic
evaluations, we collected a dataset that includes 1,085 execution-time
situations. Each situation corresponds to a state instance wherein a robot is
potentially unable to complete a task using a solution that normally works.
Experimental results show that our approach outperforms competitive baselines
from the literature in the success rate of service tasks. Additionally, we have
demonstrated COWP using a mobile manipulator. Supplementary materials are
available at: https://cowplanning.github.io/