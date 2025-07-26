---
layout: publication
title: Pre-training Graph Neural Networks For Cold-start Users And Items Representation
authors: Bowen Hao, Jing Zhang, Hongzhi Yin, Cuiping Li, Hong Chen
conference: Proceedings of the 14th ACM International Conference on Web Search and
  Data Mining
year: 2021
bibkey: hao2020pre
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.07064'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Hao et al.
---
Cold-start problem is a fundamental challenge for recommendation tasks.
Despite the recent advances on Graph Neural Networks (GNNs) incorporate the
high-order collaborative signal to alleviate the problem, the embeddings of the
cold-start users and items aren't explicitly optimized, and the cold-start
neighbors are not dealt with during the graph convolution in GNNs. This paper
proposes to pre-train a GNN model before applying it for recommendation. Unlike
the goal of recommendation, the pre-training GNN simulates the cold-start
scenarios from the users/items with sufficient interactions and takes the
embedding reconstruction as the pretext task, such that it can directly improve
the embedding quality and can be easily adapted to the new cold-start
users/items. To further reduce the impact from the cold-start neighbors, we
incorporate a self-attention-based meta aggregator to enhance the aggregation
ability of each graph convolution step, and an adaptive neighbor sampler to
select the effective neighbors according to the feedbacks from the pre-training
GNN model. Experiments on three public recommendation datasets show the
superiority of our pre-training GNN model against the original GNN models on
user/item embedding inference and the recommendation task.