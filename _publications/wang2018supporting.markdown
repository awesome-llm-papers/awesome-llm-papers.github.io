---
layout: publication
title: Supporting Very Large Models Using Automatic Dataflow Graph Partitioning
authors: Wang Minjie, Huang Chien-chin, Li Jinyang
conference: Proceedings of the Fourteenth EuroSys Conference 2019
year: 2018
bibkey: wang2018supporting
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1807.08887'}]
tags: [Alt, Tools, Training Techniques, Reinforcement Learning]
---
This paper presents Tofu, a system that partitions very large DNN models
across multiple GPU devices to reduce per-GPU memory footprint. Tofu is
designed to partition a dataflow graph of fine-grained tensor operators in
order to work transparently with a general-purpose deep learning platform like
MXNet. In order to automatically partition each operator, we propose to
describe the semantics of an operator in a simple language which represents
tensors as lambda functions mapping from tensor coordinates to values. To
optimally partition different operators in a dataflow graph, Tofu uses a
recursive search algorithm that minimizes the total communication cost. Our
experiments on an 8-GPU machine show that Tofu enables the training of very
large CNN and RNN models. It also achieves 25% - 400% speedup over alternative
approaches to train very large models.