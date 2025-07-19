---
layout: publication
title: 'Towards Large Reasoning Models: A Survey Of Reinforced Reasoning With Large
  Language Models'
authors: Xu et al.
conference: 'Findings of the Association for Computational Linguistics: ACL 2023'
year: 2025
bibkey: xu2025towards
citations: 153
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.09686'}]
tags: [Merging, Training Techniques, Survey Paper, ACL, Agentic, RAG, GPT, Reinforcement
    Learning]
---
Language has long been conceived as an essential tool for human reasoning.
The breakthrough of Large Language Models (LLMs) has sparked significant
research interest in leveraging these models to tackle complex reasoning tasks.
Researchers have moved beyond simple autoregressive token generation by
introducing the concept of "thought" -- a sequence of tokens representing
intermediate steps in the reasoning process. This innovative paradigm enables
LLMs' to mimic complex human reasoning processes, such as tree search and
reflective thinking. Recently, an emerging trend of learning to reason has
applied reinforcement learning (RL) to train LLMs to master reasoning
processes. This approach enables the automatic generation of high-quality
reasoning trajectories through trial-and-error search algorithms, significantly
expanding LLMs' reasoning capacity by providing substantially more training
data. Furthermore, recent studies demonstrate that encouraging LLMs to "think"
with more tokens during test-time inference can further significantly boost
reasoning accuracy. Therefore, the train-time and test-time scaling combined to
show a new research frontier -- a path toward Large Reasoning Model. The
introduction of OpenAI's o1 series marks a significant milestone in this
research direction. In this survey, we present a comprehensive review of recent
progress in LLM reasoning. We begin by introducing the foundational background
of LLMs and then explore the key technical components driving the development
of large reasoning models, with a focus on automated data construction,
learning-to-reason techniques, and test-time scaling. We also analyze popular
open-source projects at building large reasoning models, and conclude with open
challenges and future research directions.