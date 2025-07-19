---
layout: publication
title: 'Adapterdrop: On The Efficiency Of Adapters In Transformers'
authors: "R\xFCckl\xE9 et al."
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2020
bibkey: "r\xFCckl\xE92020adapterdrop"
citations: 127
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.11918'}]
tags: [RAG, EMNLP, Training Techniques, Transformer, Model Architecture, Efficiency
    And Optimization, Merging]
---
Massively pre-trained transformer models are computationally expensive to
fine-tune, slow for inference, and have large storage requirements. Recent
approaches tackle these shortcomings by training smaller models, dynamically
reducing the model size, and by training light-weight adapters. In this paper,
we propose AdapterDrop, removing adapters from lower transformer layers during
training and inference, which incorporates concepts from all three directions.
We show that AdapterDrop can dynamically reduce the computational overhead when
performing inference over multiple tasks simultaneously, with minimal decrease
in task performances. We further prune adapters from AdapterFusion, which
improves the inference efficiency while maintaining the task performances
entirely.