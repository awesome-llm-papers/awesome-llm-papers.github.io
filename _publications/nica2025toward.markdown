---
layout: publication
title: 'Toward Autonomous UI Exploration: The Uiexplorer Benchmark'
authors: Nica et al.
conference: Journal of Field Robotics
year: 2025
bibkey: nica2025toward
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.17779'}]
tags: [Training Techniques, Agentic, Evaluation, Reinforcement Learning, Applications,
  Fine Tuning, Datasets]
---
Autonomous agents must know how to explore user interfaces (UIs) for reliable task solving, yet systematic evaluation of this crucial phase is lacking. We introduce UIExplore-Bench, the first benchmark explicitly dedicated to UI exploration. The benchmark evaluates agents with either Structured mode (granting access to layout information like DOM trees) or Screen mode (relying on GUI-only observations such as screenshots and human-like mouse/keyboard interactions) across three levels in a standardized GitLab sandbox environment. We formalize exploration as the process of maximizing the set of actionable UI components discovered and propose a metric, human-normalized UI-Functionalities Observed (hUFO), to quantify the effectiveness of exploration. Our results show that UIExplore-AlGo achieves the leading mean hUFO scores, reaching up to 77.2% of human performance in Structured mode and 59.0% in Screen mode at 2,000 steps, particularly excelling at the Sparse level. The results highlight the relevance of our benchmark, as current agents show a substantial performance gap compared to one hour of human expert exploration, indicating ample room for future advancements. We publicly release the benchmark environment, an exploration dataset, and an evaluation suite to catalyze research into efficient UI exploration strategies and their downstream applications, such as experience-driven task completion and automated training data generation.