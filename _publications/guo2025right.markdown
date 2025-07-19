---
layout: publication
title: 'Right Is Not Enough: The Pitfalls Of Outcome Supervision In Training Llms
  For Math Reasoning'
authors: Guo et al.
conference: The American Mathematical Monthly
year: 2025
bibkey: guo2025right
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.06877'}]
tags: [Reinforcement Learning, Training Techniques, Datasets]
---
Outcome-rewarded Large Language Models (LLMs) have demonstrated remarkable success in mathematical problem-solving. However, this success often masks a critical issue: models frequently achieve correct answers through fundamentally unsound reasoning processes, a phenomenon indicative of reward hacking. We introduce MathOlympiadEval, a new dataset with fine-grained annotations, which reveals a significant gap between LLMs' answer correctness and their low process correctness. Existing automated methods like LLM-as-a-judge struggle to reliably detect these reasoning flaws. To address this, we propose ParaStepVerifier, a novel methodology for meticulous, step-by-step verification of mathematical solutions. ParaStepVerifier identifies incorrect reasoning steps. Empirical results demonstrate that ParaStepVerifier substantially improves the accuracy of identifying flawed solutions compared to baselines, especially for complex, multi-step problems. This offers a more robust path towards evaluating and training LLMs with genuine mathematical reasoning.