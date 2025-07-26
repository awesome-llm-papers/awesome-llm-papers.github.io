---
layout: publication
title: 'Agent KB: Leveraging Cross-domain Experience For Agentic Problem Solving'
authors: Xiangru Tang, Tianrui Qin, Tianhao Peng, Ziyang Zhou, Daniel Shao, Tingting
  Du, Xinming Wei, Peng Xia, Fang Wu, He Zhu, Ge Zhang, Jiaheng Liu, Xingyao Wang,
  Sirui Hong, Chenglin Wu, Hao Cheng, Chi Wang, Wangchunshu Zhou
conference: No Venue
year: 2025
bibkey: tang2025agent
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/686dc18acb5725779c60b338'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2507.06229'}]
tags: ["Agentic", "Tools"]
short_authors: Tang et al.
---
As language agents tackle increasingly complex tasks, they struggle with effective error correction and experience reuse across domains. We introduce Agent KB, a hierarchical experience framework that enables complex agentic problem solving via a novel Reason-Retrieve-Refine pipeline. Agent KB addresses a core limitation: agents traditionally cannot learn from each other's experiences. By capturing both high-level strategies and detailed execution logs, Agent KB creates a shared knowledge base that enables cross-agent knowledge transfer. Evaluated on the GAIA benchmark, Agent KB improves success rates by up to 16.28 percentage points. On the most challenging tasks, Claude-3 improves from 38.46% to 57.69%, while GPT-4 improves from 53.49% to 73.26% on intermediate tasks. On SWE-bench code repair, Agent KB enables Claude-3 to improve from 41.33% to 53.33%. Our results suggest that Agent KB provides a modular, framework-agnostic infrastructure for enabling agents to learn from past experiences and generalize successful strategies to new tasks.

https://huggingface.co/discussions/paper/686dc18acb5725779c60b338