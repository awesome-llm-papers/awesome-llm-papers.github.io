---
layout: publication
title: Efficient Retrieval Augmented Generation From Unstructured Knowledge For Task-oriented
  Dialog
authors: David Thulke, Nico Daheim, Christian Dugast, Hermann Ney
conference: Arxiv
year: 2021
citations: 29
bibkey: thulke2021efficient
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.04643'}]
tags: [RAG, Tools]
---
This paper summarizes our work on the first track of the ninth Dialog System
Technology Challenge (DSTC 9), "Beyond Domain APIs: Task-oriented
Conversational Modeling with Unstructured Knowledge Access". The goal of the
task is to generate responses to user turns in a task-oriented dialog that
require knowledge from unstructured documents. The task is divided into three
subtasks: detection, selection and generation. In order to be compute
efficient, we formulate the selection problem in terms of hierarchical
classification steps. We achieve our best results with this model.
Alternatively, we employ siamese sequence embedding models, referred to as
Dense Knowledge Retrieval, to retrieve relevant documents. This method further
reduces the computation time by a factor of more than 100x at the cost of
degradation in R@1 of 5-6% compared to the first model. Then for either
approach, we use Retrieval Augmented Generation to generate responses based on
multiple selected snippets and we show how the method can be used to fine-tune
trained embeddings.