---
layout: publication
title: 'Tabtransformer: Tabular Data Modeling Using Contextual Embeddings'
authors: Xin Huang, Ashish Khetan, Milan Cvitkovic, Zohar Karnin
conference: Arxiv
year: 2020
bibkey: huang2020tabtransformer
citations: 110
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.06678'}]
tags: ["Datasets", "Model Architecture", "Training Techniques"]
short_authors: Huang et al.
---
We propose TabTransformer, a novel deep tabular data modeling architecture
for supervised and semi-supervised learning. The TabTransformer is built upon
self-attention based Transformers. The Transformer layers transform the
embeddings of categorical features into robust contextual embeddings to achieve
higher prediction accuracy. Through extensive experiments on fifteen publicly
available datasets, we show that the TabTransformer outperforms the
state-of-the-art deep learning methods for tabular data by at least 1.0% on
mean AUC, and matches the performance of tree-based ensemble models.
Furthermore, we demonstrate that the contextual embeddings learned from
TabTransformer are highly robust against both missing and noisy data features,
and provide better interpretability. Lastly, for the semi-supervised setting we
develop an unsupervised pre-training procedure to learn data-driven contextual
embeddings, resulting in an average 2.1% AUC lift over the state-of-the-art
methods.