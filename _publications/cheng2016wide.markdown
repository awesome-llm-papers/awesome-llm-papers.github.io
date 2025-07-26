---
layout: publication
title: Wide & Deep Learning For Recommender Systems
authors: Heng-tze Cheng, Levent Koc, Jeremiah Harmsen, Tal Shaked, Tushar Chandra,
  Hrishi Aradhye, Glen Anderson, Greg Corrado, Wei Chai, Mustafa Ispir, Rohan Anil,
  Zakaria Haque, Lichan Hong, Vihan Jain, Xiaobing Liu, Hemal Shah
conference: Proceedings of the 1st Workshop on Deep Learning for Recommender Systems
year: 2016
bibkey: cheng2016wide
citations: 2990
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.07792'}]
tags: ["Applications", "Model Architecture"]
short_authors: Cheng et al.
---
Generalized linear models with nonlinear feature transformations are widely
used for large-scale regression and classification problems with sparse inputs.
Memorization of feature interactions through a wide set of cross-product
feature transformations are effective and interpretable, while generalization
requires more feature engineering effort. With less feature engineering, deep
neural networks can generalize better to unseen feature combinations through
low-dimensional dense embeddings learned for the sparse features. However, deep
neural networks with embeddings can over-generalize and recommend less relevant
items when the user-item interactions are sparse and high-rank. In this paper,
we present Wide & Deep learning---jointly trained wide linear models and deep
neural networks---to combine the benefits of memorization and generalization
for recommender systems. We productionized and evaluated the system on Google
Play, a commercial mobile app store with over one billion active users and over
one million apps. Online experiment results show that Wide & Deep significantly
increased app acquisitions compared with wide-only and deep-only models. We
have also open-sourced our implementation in TensorFlow.