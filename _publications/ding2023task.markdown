---
layout: publication
title: Task And Motion Planning With Large Language Models For Object Rearrangement
authors: Ding et al.
conference: 2023 IEEE/RSJ International Conference on Intelligent Robots and Systems
  (IROS)
year: 2023
bibkey: ding2023task
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.06247'}]
tags: [Prompting, Reinforcement Learning, Evaluation, IROS]
---
Multi-object rearrangement is a crucial skill for service robots, and
commonsense reasoning is frequently needed in this process. However, achieving
commonsense arrangements requires knowledge about objects, which is hard to
transfer to robots. Large language models (LLMs) are one potential source of
this knowledge, but they do not naively capture information about plausible
physical arrangements of the world. We propose LLM-GROP, which uses prompting
to extract commonsense knowledge about semantically valid object configurations
from an LLM and instantiates them with a task and motion planner in order to
generalize to varying scene geometry. LLM-GROP allows us to go from
natural-language commands to human-aligned object rearrangement in varied
environments. Based on human evaluations, our approach achieves the highest
rating while outperforming competitive baselines in terms of success rate while
maintaining comparable cumulative action costs. Finally, we demonstrate a
practical implementation of LLM-GROP on a mobile manipulator in real-world
scenarios. Supplementary materials are available at:
https://sites.google.com/view/llm-grop