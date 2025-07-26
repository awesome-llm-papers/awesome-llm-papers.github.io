---
layout: publication
title: Learning To Compose And Reason With Language Tree Structures For Visual Grounding
authors: Richang Hong, Daqing Liu, Xiaoyu Mo, Xiangnan He, Hanwang Zhang
conference: IEEE Transactions on Pattern Analysis and Machine Intelligence
year: 2019
bibkey: hong2019learning
citations: 144
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.01784'}]
tags: ["Llm For Code"]
short_authors: Hong et al.
---
Grounding natural language in images, such as localizing "the black dog on
the left of the tree", is one of the core problems in artificial intelligence,
as it needs to comprehend the fine-grained and compositional language space.
However, existing solutions rely on the association between the holistic
language features and visual features, while neglect the nature of
compositional reasoning implied in the language. In this paper, we propose a
natural language grounding model that can automatically compose a binary tree
structure for parsing the language and then perform visual reasoning along the
tree in a bottom-up fashion. We call our model RVG-TREE: Recursive Grounding
Tree, which is inspired by the intuition that any language expression can be
recursively decomposed into two constituent parts, and the grounding confidence
score can be recursively accumulated by calculating their grounding scores
returned by sub-trees. RVG-TREE can be trained end-to-end by using the
Straight-Through Gumbel-Softmax estimator that allows the gradients from the
continuous score functions passing through the discrete tree construction.
Experiments on several benchmarks show that our model achieves the
state-of-the-art performance with more explainable reasoning.