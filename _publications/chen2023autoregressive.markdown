---
layout: publication
title: 'Autotamp: Autoregressive Task And Motion Planning With Llms As Translators
  And Checkers'
authors: Yongchao Chen et al.
conference: The 2024 International Conference on Robotics and Automation
year: 2023
citations: 21
bibkey: chen2023autoregressive
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.06531'}, {name: Code,
    url: 'https://yongchao98.github.io/MIT-REALM-AutoTAMP/'}]
tags: [Has Code, Few-Shot, GPT, Prompting]
---
For effective human-robot interaction, robots need to understand, plan, and
execute complex, long-horizon tasks described by natural language. Recent
advances in large language models (LLMs) have shown promise for translating
natural language into robot action sequences for complex tasks. However,
existing approaches either translate the natural language directly into robot
trajectories or factor the inference process by decomposing language into task
sub-goals and relying on a motion planner to execute each sub-goal. When
complex environmental and temporal constraints are involved, inference over
planning tasks must be performed jointly with motion plans using traditional
task-and-motion planning (TAMP) algorithms, making factorization into subgoals
untenable. Rather than using LLMs to directly plan task sub-goals, we instead
perform few-shot translation from natural language task descriptions to an
intermediate task representation that can then be consumed by a TAMP algorithm
to jointly solve the task and motion plan. To improve translation, we
automatically detect and correct both syntactic and semantic errors via
autoregressive re-prompting, resulting in significant improvements in task
completion. We show that our approach outperforms several methods using LLMs as
planners in complex task domains. See our project website
https://yongchao98.github.io/MIT-REALM-AutoTAMP/ for prompts, videos, and code.