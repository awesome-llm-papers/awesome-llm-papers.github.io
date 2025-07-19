---
layout: publication
title: 'Perceiver IO: A General Architecture For Structured Inputs & Outputs'
authors: Jaegle et al.
conference: Arxiv
year: 2021
bibkey: jaegle2021perceiver
citations: 171
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.14795'}]
tags: [Evaluation, BERT, Tokenization, Model Architecture, Transformer, Reinforcement
    Learning, Datasets]
---
A central goal of machine learning is the development of systems that can
solve many problems in as many data domains as possible. Current architectures,
however, cannot be applied beyond a small set of stereotyped settings, as they
bake in domain & task assumptions or scale poorly to large inputs or outputs.
In this work, we propose Perceiver IO, a general-purpose architecture that
handles data from arbitrary settings while scaling linearly with the size of
inputs and outputs. Our model augments the Perceiver with a flexible querying
mechanism that enables outputs of various sizes and semantics, doing away with
the need for task-specific architecture engineering. The same architecture
achieves strong results on tasks spanning natural language and visual
understanding, multi-task and multi-modal reasoning, and StarCraft II. As
highlights, Perceiver IO outperforms a Transformer-based BERT baseline on the
GLUE language benchmark despite removing input tokenization and achieves
state-of-the-art performance on Sintel optical flow estimation with no explicit
mechanisms for multiscale correspondence.