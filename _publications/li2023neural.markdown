---
layout: publication
title: Neural Machine Translation With Dynamic Graph Convolutional Decoder
authors: Li et al.
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2023
bibkey: li2023neural
citations: 233
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.17698'}]
tags: [Model Architecture, Tools, Evaluation, EMNLP, RAG, Datasets]
---
Existing wisdom demonstrates the significance of syntactic knowledge for the
improvement of neural machine translation models. However, most previous works
merely focus on leveraging the source syntax in the well-known encoder-decoder
framework. In sharp contrast, this paper proposes an end-to-end translation
architecture from the (graph \& sequence) structural inputs to the (graph \&
sequence) outputs, where the target translation and its corresponding syntactic
graph are jointly modeled and generated. We propose a customized Dynamic
Spatial-Temporal Graph Convolutional Decoder (Dyn-STGCD), which is designed for
consuming source feature representations and their syntactic graph, and
auto-regressively generating the target syntactic graph and tokens
simultaneously. We conduct extensive experiments on five widely acknowledged
translation benchmarks, verifying that our proposal achieves consistent
improvements over baselines and other syntax-aware variants.