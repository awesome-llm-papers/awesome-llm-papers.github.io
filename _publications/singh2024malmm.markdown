---
layout: publication
title: 'MALMM: Multi-agent Large Language Models For Zero-shot Robotics Manipulation'
authors: Singh et al.
conference: Proceedings of the 32nd ACM International Conference on Information and
  Knowledge Management
year: 2024
bibkey: singh2024malmm
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.17636'}]
tags: [RAG, Agentic, Tools, In Context Learning, CIKM, Reinforcement Learning, LLM
    For Code]
---
Large Language Models (LLMs) have demonstrated remarkable planning abilities
across various domains, including robotics manipulation and navigation. While
recent efforts in robotics have leveraged LLMs both for high-level and
low-level planning, these approaches often face significant challenges, such as
hallucinations in long-horizon tasks and limited adaptability due to the
generation of plans in a single pass without real-time feedback. To address
these limitations, we propose a novel multi-agent LLM framework, Multi-Agent
Large Language Model for Manipulation (MALMM) that distributes high-level
planning and low-level control code generation across specialized LLM agents,
supervised by an additional agent that dynamically manages transitions. By
incorporating observations from the environment after each step, our framework
effectively handles intermediate failures and enables adaptive re-planning.
Unlike existing methods, our approach does not rely on pre-trained skill
policies or in-context learning examples and generalizes to a variety of new
tasks. We evaluate our approach on nine RLBench tasks, including long-horizon
tasks, and demonstrate its ability to solve robotics manipulation in a
zero-shot setting, thereby overcoming key limitations of existing LLM-based
manipulation methods.