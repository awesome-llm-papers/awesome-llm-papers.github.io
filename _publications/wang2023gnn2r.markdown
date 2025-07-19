---
layout: publication
title: 'GNN2R: Weakly-supervised Rationale-providing Question Answering Over Knowledge
  Graphs'
authors: Wang et al.
conference: Proceedings of the VLDB Endowment
year: 2023
bibkey: wang2023gnn2r
citations: 86
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.02317'}]
tags: [Interpretability And Explainability, Efficiency And Optimization, Reinforcement
    Learning]
---
Most current methods for multi-hop question answering (QA) over knowledge
graphs (KGs) only provide final conclusive answers without explanations, such
as a set of KG entities that is difficult for normal users to review and
comprehend. This issue severely limits the application of KG-based QA in
real-world scenarios. However, it is non-trivial to solve due to two
challenges: First, annotations of reasoning chains of multi-hop questions,
which could serve as supervision for explanation generation, are usually
lacking. Second, it is difficult to maintain high efficiency when explicit KG
triples need to be retrieved to generate explanations. In this paper, we
propose a novel Graph Neural Network-based Two-Step Reasoning model (GNN2R) to
solve this issue. GNN2R can provide both final answers and reasoning subgraphs
as a rationale behind final answers efficiently with only weak supervision that
is available through question-final answer pairs. We extensively evaluated
GNN2R with detailed analyses in experiments. The results demonstrate that, in
terms of effectiveness, efficiency, and quality of generated explanations,
GNN2R outperforms existing state-of-the-art methods that are applicable to this
task. Our code and pre-trained models are available at
https://github.com/ruijie-wang-uzh/GNN2R.