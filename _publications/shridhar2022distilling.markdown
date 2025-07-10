---
layout: publication
title: Distilling Reasoning Capabilities Into Smaller Language Models
authors: Kumar Shridhar, Alessandro Stolfo, Mrinmaya Sachan
conference: 'Findings of the Association for Computational Linguistics: ACL 2023'
year: 2022
citations: 22
bibkey: shridhar2022distilling
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.00193'}, {name: Code,
    url: 'https://github.com/kumar-shridhar/Distiiling-LM'}]
tags: [Has Code, Model Architecture, Distillation, RAG, Efficiency and Optimization,
  GPT]
---
Step-by-step reasoning approaches like chain of thought (CoT) have proved to
be very effective in inducing reasoning capabilities in large language models.
However, the success of the CoT approach is fundamentally tied to the model
size, and billion parameter-scale models are often needed to get CoT to work.
In this paper, we propose a knowledge distillation approach that leverages the
step-by-step CoT reasoning capabilities of larger models and distills these
abilities into smaller models.
  In this work, we propose an alternative reasoning scheme, Socratic CoT, that
learns a decomposition of the original problem into a sequence of subproblems
and uses it to guide the intermediate reasoning steps. We use Socratic CoT to
train a combination of two small distilled models: a problem decomposer and a
subproblem solver. In practice, given a new problem, the two distilled models
work in sync to decompose and solve complex problems. On multiple reasoning
datasets (GSM8K, StrategyQA, and SVAMP), our proposed distillation strategies
boosts the performance of smaller models over 70% compared to the baselines.
Finally, we investigate when Socratic CoT is an effective alternative to CoT,
demonstrating cases where a much smaller model (GPT-2 large) can outperform a
10X larger model (GPT-3 6B). Our code is available here:
https://github.com/kumar-shridhar/Distiiling-LM