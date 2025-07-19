---
layout: publication
title: Improving Knowledge Tracing Via Pre-training Question Embeddings
authors: Liu et al.
conference: Proceedings of the Twenty-Ninth International Joint Conference on Artificial
  Intelligence
year: 2020
bibkey: liu2020improving
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.05031'}]
tags: [Training Techniques, AAAI, IJCAI, Datasets, Alt]
---
Knowledge tracing (KT) defines the task of predicting whether students can
correctly answer questions based on their historical response. Although much
research has been devoted to exploiting the question information, plentiful
advanced information among questions and skills hasn't been well extracted,
making it challenging for previous work to perform adequately. In this paper,
we demonstrate that large gains on KT can be realized by pre-training
embeddings for each question on abundant side information, followed by training
deep KT models on the obtained embeddings. To be specific, the side information
includes question difficulty and three kinds of relations contained in a
bipartite graph between questions and skills. To pre-train the question
embeddings, we propose to use product-based neural networks to recover the side
information. As a result, adopting the pre-trained embeddings in existing deep
KT models significantly outperforms state-of-the-art baselines on three common
KT datasets.