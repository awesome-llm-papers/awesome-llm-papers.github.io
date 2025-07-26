---
layout: publication
title: Augmenting Neural Networks With First-order Logic
authors: Tao Li, Vivek Srikumar
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: li2019augmenting
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.06298'}]
tags: ["Datasets", "RAG", "Tools", "Training Techniques"]
short_authors: Tao Li, Vivek Srikumar
---
Today, the dominant paradigm for training neural networks involves minimizing
task loss on a large dataset. Using world knowledge to inform a model, and yet
retain the ability to perform end-to-end training remains an open question. In
this paper, we present a novel framework for introducing declarative knowledge
to neural network architectures in order to guide training and prediction. Our
framework systematically compiles logical statements into computation graphs
that augment a neural network without extra learnable parameters or manual
redesign. We evaluate our modeling strategy on three tasks: machine
comprehension, natural language inference, and text chunking. Our experiments
show that knowledge-augmented networks can strongly improve over baselines,
especially in low-data regimes.