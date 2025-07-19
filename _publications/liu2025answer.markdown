---
layout: publication
title: Answer Convergence As A Signal For Early Stopping In Reasoning
authors: Liu Xin, Wang Lu
conference: The Annals of Statistics
year: 2025
bibkey: liu2025answer
citations: 241
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.02536'}]
tags: [Prompting, Evaluation, Efficiency And Optimization, Reinforcement Learning,
  Applications, Datasets]
---
Chain-of-thought (CoT) prompting enhances reasoning in large language models (LLMs) but often leads to verbose and redundant outputs, thus increasing inference cost. We hypothesize that many reasoning steps are unnecessary for producing correct answers. To investigate this, we start with a systematic study to examine what is the minimum reasoning required for a model to reach a stable decision. We find that on math reasoning tasks like math, models typically converge to their final answers after 60% of the reasoning steps, suggesting substantial redundancy in the remaining content. Based on these insights, we propose three inference-time strategies to improve efficiency: (1) early stopping via answer consistency, (2) boosting the probability of generating end-of-reasoning signals, and (3) a supervised method that learns when to stop based on internal activations. Experiments across five benchmarks and five open-weights LLMs show that our methods significantly reduce token usage with little or no accuracy drop. In particular, on NaturalQuestions, Answer Consistency reduces tokens by over 40% while further improving accuracy. Our work underscores the importance of cost-effective reasoning methods that operate at inference time, offering practical benefits for real-world applications.