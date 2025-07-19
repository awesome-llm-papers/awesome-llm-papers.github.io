---
layout: publication
title: A Self-attentional Neural Architecture For Code Completion With Multi-task
  Learning
authors: Liu et al.
conference: Proceedings of the 28th International Conference on Program Comprehension
year: 2019
bibkey: liu2019self
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.06983'}]
tags: [Attention Mechanism, Tools, Transformer, Model Architecture, Reinforcement
    Learning, Datasets, LLM For Code]
---
Code completion, one of the most useful features in the Integrated
Development Environments (IDEs), can accelerate software development by
suggesting the libraries, APIs, and method names in real-time. Recent studies
have shown that statistical language models can improve the performance of code
completion tools through learning from large-scale software repositories.
However, these models suffer from three major drawbacks: a) The hierarchical
structural information of the programs is not fully utilized in the program's
representation; b) In programs, the semantic relationships can be very long.
Existing recurrent neural networks based language models are not sufficient to
model the long-term dependency. c) Existing approaches perform a specific task
in one model, which leads to the underuse of the information from related
tasks. To address these challenges, in this paper, we propose a
self-attentional neural architecture for code completion with multi-task
learning. To utilize the hierarchical structural information of the programs,
we present a novel method that considers the path from the predicting node to
the root node. To capture the long-term dependency in the input programs, we
adopt a self-attentional architecture based network as the base language model.
To enable the knowledge sharing between related tasks, we creatively propose a
Multi-Task Learning (MTL) framework to learn two related tasks in code
completion jointly. Experiments on three real-world datasets demonstrate the
effectiveness of our model when compared with state-of-the-art methods.