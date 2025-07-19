---
layout: publication
title: 'Tell-drive: Enhancing Autonomous Driving With Teacher Llm-guided Deep Reinforcement
  Learning'
authors: Xu et al.
conference: Electronic Imaging
year: 2025
bibkey: xu2025tell
citations: 742
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.01387'}]
tags: [RAG, Attention Mechanism, Alt, Prompting, Agentic, Tools, Evaluation, Transformer,
  Model Architecture, Reinforcement Learning, Security, Fine Tuning, Merging]
---
Although Deep Reinforcement Learning (DRL) and Large Language Models (LLMs)
each show promise in addressing decision-making challenges in autonomous
driving, DRL often suffers from high sample complexity, while LLMs have
difficulty ensuring real-time decision making. To address these limitations, we
propose TeLL-Drive, a hybrid framework that integrates a Teacher LLM to guide
an attention-based Student DRL policy. By incorporating risk metrics,
historical scenario retrieval, and domain heuristics into context-rich prompts,
the LLM produces high-level driving strategies through chain-of-thought
reasoning. A self-attention mechanism then fuses these strategies with the DRL
agent's exploration, accelerating policy convergence and boosting robustness
across diverse driving conditions. The experimental results, evaluated across
multiple traffic scenarios, show that TeLL-Drive outperforms existing baseline
methods, including other LLM-based approaches, in terms of success rates,
average returns, and real-time feasibility. Ablation studies underscore the
importance of each model component, especially the synergy between the
attention mechanism and LLM-driven guidance. Finally, we build a virtual-real
fusion experimental platform to verify the real-time performance, robustness,
and reliability of the algorithm running on real vehicles through
vehicle-in-loop experiments.