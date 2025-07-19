---
layout: publication
title: Neural Program Repair With Execution-based Backpropagation
authors: Ye He, Martinez Matias, Monperrus Martin
conference: Proceedings of the 44th International Conference on Software Engineering
year: 2021
bibkey: ye2021neural
citations: 99
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.04123'}]
tags: [Model Architecture, Efficiency And Optimization, Evaluation, LLM For Code,
  LLM for Code, Datasets, Reinforcement Learning]
---
Neural machine translation (NMT) architectures have achieved promising
results for automatic program repair. Yet, they have the limitation of
generating low-quality patches (e.g., not compilable patches). This is because
the existing works only optimize a purely syntactic loss function based on
characters and tokens without incorporating program-specific information during
neural network weight optimization. In this paper, we propose a novel program
repair model called RewardRepair. The core novelty of RewardRepair is to
improve NMT-based program repair with a loss function based on program
compilation and test execution information, rewarding the network to produce
patches that compile and that do not overfit. We conduct several experiments to
evaluate RewardRepair showing that it is feasible and effective to use
compilation and test execution results to optimize the underlying neural repair
model. RewardRepair correctly repairs 207 bugs over four benchmarks. we report
on repair success for 121 bugs that are fixed for the first time in the
literature. Also, RewardRepair produces up to 45.3% of compilable patches, an
improvement over the 39% by the state-of-the-art.