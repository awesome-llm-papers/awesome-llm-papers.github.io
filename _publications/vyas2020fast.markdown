---
layout: publication
title: Fast Transformers With Clustered Attention
authors: "Vyas Apoorv, Katharopoulos Angelos, Fleuret Fran\xE7ois"
conference: Arxiv
year: 2020
bibkey: vyas2020fast
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.04825'}]
tags: [Attention Mechanism, Evaluation, Transformer, BERT, Model Architecture, Time
    Series, Datasets]
---
Transformers have been proven a successful model for a variety of tasks in
sequence modeling. However, computing the attention matrix, which is their key
component, has quadratic complexity with respect to the sequence length, thus
making them prohibitively expensive for large sequences. To address this, we
propose clustered attention, which instead of computing the attention for every
query, groups queries into clusters and computes attention just for the
centroids. To further improve this approximation, we use the computed clusters
to identify the keys with the highest attention per query and compute the exact
key/query dot products. This results in a model with linear complexity with
respect to the sequence length for a fixed number of clusters. We evaluate our
approach on two automatic speech recognition datasets and show that our model
consistently outperforms vanilla transformers for a given computational budget.
Finally, we demonstrate that our model can approximate arbitrarily complex
attention distributions with a minimal number of clusters by approximating a
pretrained BERT model on GLUE and SQuAD benchmarks with only 25 clusters and no
loss in performance.