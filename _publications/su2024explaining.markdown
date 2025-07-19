---
layout: publication
title: 'Explaining Hypergraph Neural Networks: From Local Explanations To Global Concepts'
authors: Su et al.
conference: Proceedings of the 2019 AAAI/ACM Conference on AI, Ethics, and Society
year: 2024
bibkey: su2024explaining
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.07764'}]
tags: [Interpretability And Explainability, Datasets, RAG, Attention Mechanism, Ethics
    And Bias, Model Architecture, Reinforcement Learning, AAAI, Responsible AI]
---
Hypergraph neural networks are a class of powerful models that leverage the
message passing paradigm to learn over hypergraphs, a generalization of graphs
well-suited to describing relational data with higher-order interactions.
However, such models are not naturally interpretable, and their explainability
has received very limited attention. We introduce SHypX, the first
model-agnostic post-hoc explainer for hypergraph neural networks that provides
both local and global explanations. At the instance-level, it performs input
attribution by discretely sampling explanation subhypergraphs optimized to be
faithful and concise. At the model-level, it produces global explanation
subhypergraphs using unsupervised concept extraction. Extensive experiments
across four real-world and four novel, synthetic hypergraph datasets
demonstrate that our method finds high-quality explanations which can target a
user-specified balance between faithfulness and concision, improving over
baselines by 25 percent points in fidelity on average.