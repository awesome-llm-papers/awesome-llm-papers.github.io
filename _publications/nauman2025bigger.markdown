---
layout: publication
title: 'Bigger, Regularized, Categorical: High-capacity Value Functions Are Efficient
  Multi-task Learners'
authors: Nauman et al.
conference: Proceedings of the tenth ACM SIGKDD international conference on Knowledge
  discovery and data mining
year: 2025
bibkey: nauman2025bigger
citations: 810
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.23150'}]
tags: [Training Techniques, Agentic, Evaluation, Efficiency And Optimization, Language
    Modeling, Reinforcement Learning, Datasets, KDD]
---
Recent advances in language modeling and vision stem from training large models on diverse, multi-task data. This paradigm has had limited impact in value-based reinforcement learning (RL), where improvements are often driven by small models trained in a single-task context. This is because in multi-task RL sparse rewards and gradient conflicts make optimization of temporal difference brittle. Practical workflows for generalist policies therefore avoid online training, instead cloning expert trajectories or distilling collections of single-task policies into one agent. In this work, we show that the use of high-capacity value models trained via cross-entropy and conditioned on learnable task embeddings addresses the problem of task interference in online RL, allowing for robust and scalable multi-task training. We test our approach on 7 multi-task benchmarks with over 280 unique tasks, spanning high degree-of-freedom humanoid control and discrete vision-based RL. We find that, despite its simplicity, the proposed approach leads to state-of-the-art single and multi-task performance, as well as sample-efficient transfer to new tasks.