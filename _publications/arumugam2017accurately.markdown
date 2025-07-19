---
layout: publication
title: Accurately And Efficiently Interpreting Human-robot Instructions Of Varying
  Granularities
authors: Arumugam et al.
conference: 'Robotics: Science and Systems XIII'
year: 2017
bibkey: arumugam2017accurately
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1704.06616'}]
tags: [RAG, Tools, RSS, Efficiency And Optimization, Reinforcement Learning]
---
Humans can ground natural language commands to tasks at both abstract and
fine-grained levels of specificity. For instance, a human forklift operator can
be instructed to perform a high-level action, like "grab a pallet" or a
low-level action like "tilt back a little bit." While robots are also capable
of grounding language commands to tasks, previous methods implicitly assume
that all commands and tasks reside at a single, fixed level of abstraction.
Additionally, methods that do not use multiple levels of abstraction encounter
inefficient planning and execution times as they solve tasks at a single level
of abstraction with large, intractable state-action spaces closely resembling
real world complexity. In this work, by grounding commands to all the tasks or
subtasks available in a hierarchical planning framework, we arrive at a model
capable of interpreting language at multiple levels of specificity ranging from
coarse to more granular. We show that the accuracy of the grounding procedure
is improved when simultaneously inferring the degree of abstraction in language
used to communicate the task. Leveraging hierarchy also improves efficiency:
our proposed approach enables a robot to respond to a command within one second
on 90% of our tasks, while baselines take over twenty seconds on half the
tasks. Finally, we demonstrate that a real, physical robot can ground commands
at multiple levels of abstraction allowing it to efficiently plan different
subtasks within the same planning hierarchy.