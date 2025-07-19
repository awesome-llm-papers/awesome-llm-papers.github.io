---
layout: publication
title: Stepwise Self-consistent Mathematical Reasoning With Large Language Models
authors: Zhao et al.
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 5: Industry Track)'
year: 2024
bibkey: zhao2024stepwise
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.17786'}]
tags: [Datasets, ACL, Fine Tuning, Evaluation]
---
Using Large Language Models for complex mathematical reasoning is difficult,
primarily due to the complexity of multi-step reasoning. The main challenges of
this process include (1) selecting critical intermediate results to advance the
procedure, and (2) limited exploration of potential solutions. To address these
issues, we introduce a novel algorithm, namely Stepwise Self-Consistent
Chain-of-Thought (SSC-CoT). SSC-CoT employs a strategy of selecting
intermediate steps based on the intersection of various reasoning chains.
Additionally, SSC-CoT enables the model to discover critical intermediate steps
by querying a knowledge graph comprising relevant domain knowledge. To validate
SSC-CoT, we present a new dataset, TriMaster100, tailored for complex
trigonometry problems. This dataset contains 100 questions, with each solution
broken down into scored intermediate steps, facilitating a comprehensive
evaluation of the mathematical reasoning process. On TriMaster100, SSC-CoT
triples the effectiveness of the state-of-the-art methods. Furthermore, we
benchmark SSC-CoT on the widely recognized complex mathematical question
dataset, MATH level 5, and it surpasses the second-best method by 7.2% in
accuracy. Code and the TriMaster100 dataset can be found at:
https://github.com/zhao-zilong/ssc-cot.