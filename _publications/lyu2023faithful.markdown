---
layout: publication
title: Faithful Chain-of-thought Reasoning
authors: Qing Lyu et al.
conference: 'Proceedings of the 13th International Joint Conference on Natural Language
  Processing and the 3rd Conference of the Asia-Pacific Chapter of the Association
  for Computational Linguistics (Volume 1: Long Papers)'
year: 2023
citations: 42
bibkey: lyu2023faithful
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2301.13379v3'}]
tags: [Model Architecture, Few-Shot, Interpretability and Explainability, Tools, Prompting,
  GPT, Evaluation]
---
While Chain-of-Thought (CoT) prompting boosts Language Models' (LM)
performance on a gamut of complex reasoning tasks, the generated reasoning
chain does not necessarily reflect how the model arrives at the answer (aka.
faithfulness). We propose Faithful CoT, a reasoning framework involving two
stages: Translation (Natural Language query \\(\rightarrow\\) symbolic reasoning
chain) and Problem Solving (reasoning chain \\(\rightarrow\\) answer), using an LM
and a deterministic solver respectively. This guarantees that the reasoning
chain provides a faithful explanation of the final answer. Aside from
interpretability, Faithful CoT also improves empirical performance: it
outperforms standard CoT on 9 of 10 benchmarks from 4 diverse domains, with a
relative accuracy gain of 6.3% on Math Word Problems (MWP), 3.4% on Planning,
5.5% on Multi-hop Question Answering (QA), and 21.4% on Relational Inference.
Furthermore, with GPT-4 and Codex, it sets the new state-of-the-art few-shot
performance on 7 datasets (with 95.0+ accuracy on 6 of them), showing a strong
synergy between faithfulness and accuracy.