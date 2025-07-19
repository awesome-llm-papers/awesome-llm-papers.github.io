---
layout: publication
title: General Item Representation Learning For Cold-start Content Recommendations
authors: Kim et al.
conference: Proceedings of the 8th ACM Conference on Recommender systems
year: 2024
bibkey: kim2024general
citations: 127
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.13808'}]
tags: [Model Architecture, Tools, RecSys, Evaluation, Transformer, Multimodal Models,
  Datasets, Reinforcement Learning]
---
Cold-start item recommendation is a long-standing challenge in recommendation
systems. A common remedy is to use a content-based approach, but rich
information from raw contents in various forms has not been fully utilized. In
this paper, we propose a domain/data-agnostic item representation learning
framework for cold-start recommendations, naturally equipped with multimodal
alignment among various features by adopting a Transformer-based architecture.
Our proposed model is end-to-end trainable completely free from classification
labels, not just costly to collect but suboptimal for recommendation-purpose
representation learning. From extensive experiments on real-world movie and
news recommendation benchmarks, we verify that our approach better preserves
fine-grained user taste than state-of-the-art baselines, universally applicable
to multiple domains at large scale.