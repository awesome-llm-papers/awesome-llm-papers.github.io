---
layout: publication
title: Open-vocabulary Queryable Scene Representations For Real World Planning
authors: Boyuan Chen, Fei Xia, Brian Ichter, Kanishka Rao, Keerthana Gopalakrishnan,
  Michael S. Ryoo, Austin Stone, Daniel Kappler
conference: 2023 IEEE International Conference on Robotics and Automation (ICRA)
year: 2023
bibkey: chen2022open
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2209.09874'}]
tags: ["Has Code", "ICRA", "Tools"]
short_authors: Chen et al.
---
Large language models (LLMs) have unlocked new capabilities of task planning
from human instructions. However, prior attempts to apply LLMs to real-world
robotic tasks are limited by the lack of grounding in the surrounding scene. In
this paper, we develop NLMap, an open-vocabulary and queryable scene
representation to address this problem. NLMap serves as a framework to gather
and integrate contextual information into LLM planners, allowing them to see
and query available objects in the scene before generating a
context-conditioned plan. NLMap first establishes a natural language queryable
scene representation with Visual Language models (VLMs). An LLM based object
proposal module parses instructions and proposes involved objects to query the
scene representation for object availability and location. An LLM planner then
plans with such information about the scene. NLMap allows robots to operate
without a fixed list of objects nor executable options, enabling real robot
operation unachievable by previous methods. Project website:
https://nlmap-saycan.github.io