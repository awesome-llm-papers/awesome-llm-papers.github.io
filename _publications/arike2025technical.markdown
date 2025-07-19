---
layout: publication
title: 'Technical Report: Evaluating Goal Drift In Language Model Agents'
authors: Arike et al.
conference: International Journal of Intelligent Systems
year: 2025
bibkey: arike2025technical
citations: 194
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.02709'}]
tags: [Prompting, Agentic, Reinforcement Learning, Evaluation]
---
As language models (LMs) are increasingly deployed as autonomous agents,
their robust adherence to human-assigned objectives becomes crucial for safe
operation. When these agents operate independently for extended periods without
human oversight, even initially well-specified goals may gradually shift.
Detecting and measuring goal drift - an agent's tendency to deviate from its
original objective over time - presents significant challenges, as goals can
shift gradually, causing only subtle behavioral changes. This paper proposes a
novel approach to analyzing goal drift in LM agents. In our experiments, agents
are first explicitly given a goal through their system prompt, then exposed to
competing objectives through environmental pressures. We demonstrate that while
the best-performing agent (a scaffolded version of Claude 3.5 Sonnet) maintains
nearly perfect goal adherence for more than 100,000 tokens in our most
difficult evaluation setting, all evaluated models exhibit some degree of goal
drift. We also find that goal drift correlates with models' increasing
susceptibility to pattern-matching behaviors as the context length grows.