---
layout: publication
title: Large-batch Training For LSTM And Beyond
authors: You et al.
conference: Proceedings of the International Conference for High Performance Computing,
  Networking, Storage and Analysis
year: 2019
bibkey: you2019large
citations: 74
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1901.08256'}]
tags: [Model Architecture, Interpretability And Explainability, Training Techniques,
  Pre-Training, Applications, RAG]
---
Large-batch training approaches have enabled researchers to utilize
large-scale distributed processing and greatly accelerate deep-neural net (DNN)
training. For example, by scaling the batch size from 256 to 32K, researchers
have been able to reduce the training time of ResNet50 on ImageNet from 29
hours to 2.2 minutes (Ying et al., 2018). In this paper, we propose a new
approach called linear-epoch gradual-warmup (LEGW) for better large-batch
training. With LEGW, we are able to conduct large-batch training for both CNNs
and RNNs with the Sqrt Scaling scheme. LEGW enables Sqrt Scaling scheme to be
useful in practice and as a result we achieve much better results than the
Linear Scaling learning rate scheme. For LSTM applications, we are able to
scale the batch size by a factor of 64 without losing accuracy and without
tuning the hyper-parameters. For CNN applications, LEGW is able to achieve the
same accuracy even as we scale the batch size to 32K. LEGW works better than
previous large-batch auto-tuning techniques. LEGW achieves a 5.3X average
speedup over the baselines for four LSTM-based applications on the same
hardware. We also provide some theoretical explanations for LEGW.