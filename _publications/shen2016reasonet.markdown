---
layout: publication
title: 'Reasonet: Learning To Stop Reading In Machine Comprehension'
authors: Yelong Shen, Po-sen Huang, Jianfeng Gao, Weizhu Chen
conference: Arxiv
year: 2016
bibkey: shen2016reasonet
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1609.05284'}]
tags: ["Datasets", "Model Architecture", "Reinforcement Learning"]
short_authors: Shen et al.
---
Teaching a computer to read and answer general questions pertaining to a
document is a challenging yet unsolved problem. In this paper, we describe a
novel neural network architecture called the Reasoning Network (ReasoNet) for
machine comprehension tasks. ReasoNets make use of multiple turns to
effectively exploit and then reason over the relation among queries, documents,
and answers. Different from previous approaches using a fixed number of turns
during inference, ReasoNets introduce a termination state to relax this
constraint on the reasoning depth. With the use of reinforcement learning,
ReasoNets can dynamically determine whether to continue the comprehension
process after digesting intermediate results, or to terminate reading when it
concludes that existing information is adequate to produce an answer. ReasoNets
have achieved exceptional performance in machine comprehension datasets,
including unstructured CNN and Daily Mail datasets, the Stanford SQuAD dataset,
and a structured Graph Reachability dataset.