---
layout: publication
title: Learning To Compose Task-specific Tree Structures
authors: Choi Jihun, Yoo Kang Min, Lee Sang-goo
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2017
bibkey: choi2017learning
citations: 160
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.02786'}]
tags: [Model Architecture, AAAI]
---
For years, recursive neural networks (RvNNs) have been shown to be suitable
for representing text into fixed-length vectors and achieved good performance
on several natural language processing tasks. However, the main drawback of
RvNNs is that they require structured input, which makes data preparation and
model implementation hard. In this paper, we propose Gumbel Tree-LSTM, a novel
tree-structured long short-term memory architecture that learns how to compose
task-specific tree structures only from plain text data efficiently. Our model
uses Straight-Through Gumbel-Softmax estimator to decide the parent node among
candidates dynamically and to calculate gradients of the discrete decision. We
evaluate the proposed model on natural language inference and sentiment
analysis, and show that our model outperforms or is at least comparable to
previous models. We also find that our model converges significantly faster
than other models.