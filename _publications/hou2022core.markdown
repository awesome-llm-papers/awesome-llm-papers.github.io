---
layout: publication
title: 'CORE: Simple And Effective Session-based Recommendation Within Consistent
  Representation Space'
authors: Hou et al.
conference: Proceedings of the 45th International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2022
bibkey: hou2022core
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.11067'}]
tags: [Tools, Efficiency And Optimization, Reinforcement Learning, SIGIR, Datasets]
---
Session-based Recommendation (SBR) refers to the task of predicting the next
item based on short-term user behaviors within an anonymous session. However,
session embedding learned by a non-linear encoder is usually not in the same
representation space as item embeddings, resulting in the inconsistent
prediction issue while recommending items. To address this issue, we propose a
simple and effective framework named CORE, which can unify the representation
space for both the encoding and decoding processes. Firstly, we design a
representation-consistent encoder that takes the linear combination of input
item embeddings as session embedding, guaranteeing that sessions and items are
in the same representation space. Besides, we propose a robust distance
measuring method to prevent overfitting of embeddings in the consistent
representation space. Extensive experiments conducted on five public real-world
datasets demonstrate the effectiveness and efficiency of the proposed method.
The code is available at: https://github.com/RUCAIBox/CORE.