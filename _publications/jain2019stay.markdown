---
layout: publication
title: 'Stay On The Path: Instruction Fidelity In Vision-and-language Navigation'
authors: Vihan Jain, Gabriel Magalhaes, Alexander Ku, Ashish Vaswani, Eugene Ie, Jason
  Baldridge
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: jain2019stay
citations: 131
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.12255'}]
tags: ["Datasets", "Evaluation"]
short_authors: Jain et al.
---
Advances in learning and representations have reinvigorated work that
connects language to other modalities. A particularly exciting direction is
Vision-and-Language Navigation(VLN), in which agents interpret natural language
instructions and visual scenes to move through environments and reach goals.
Despite recent progress, current research leaves unclear how much of a role
language understanding plays in this task, especially because dominant
evaluation metrics have focused on goal completion rather than the sequence of
actions corresponding to the instructions. Here, we highlight shortcomings of
current metrics for the Room-to-Room dataset (Anderson et al.,2018b) and
propose a new metric, Coverage weighted by Length Score (CLS). We also show
that the existing paths in the dataset are not ideal for evaluating instruction
following because they are direct-to-goal shortest paths. We join existing
short paths to form more challenging extended paths to create a new data set,
Room-for-Room (R4R). Using R4R and CLS, we show that agents that receive
rewards for instruction fidelity outperform agents that focus on goal
completion.