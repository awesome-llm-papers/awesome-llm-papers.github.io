---
layout: publication
title: 'Atman: Understanding Transformer Predictions Through Memory Efficient Attention
  Manipulation'
authors: Deiseroth et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: deiseroth2023atman
citations: 361
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2301.08110'}]
tags: [Interpretability And Explainability, Attention Mechanism, Evaluation, CVPR,
  Transformer, Model Architecture, Applications, Datasets]
---
Generative transformer models have become increasingly complex, with large
numbers of parameters and the ability to process multiple input modalities.
Current methods for explaining their predictions are resource-intensive. Most
crucially, they require prohibitively large amounts of extra memory, since they
rely on backpropagation which allocates almost twice as much GPU memory as the
forward pass. This makes it difficult, if not impossible, to use them in
production. We present AtMan that provides explanations of generative
transformer models at almost no extra cost. Specifically, AtMan is a
modality-agnostic perturbation method that manipulates the attention mechanisms
of transformers to produce relevance maps for the input with respect to the
output prediction. Instead of using backpropagation, AtMan applies a
parallelizable token-based search method based on cosine similarity
neighborhood in the embedding space. Our exhaustive experiments on text and
image-text benchmarks demonstrate that AtMan outperforms current
state-of-the-art gradient-based methods on several metrics while being
computationally efficient. As such, AtMan is suitable for use in large model
inference deployments.