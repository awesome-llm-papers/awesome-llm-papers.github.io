---
layout: publication
title: 'Adapterdrop: On The Efficiency Of Adapters In Transformers'
authors: "Andreas R\xFCckl\xE9, Gregor Geigle, Max Glockner, Tilman Beck, Jonas Pfeiffer,\
  \ Nils Reimers, Iryna Gurevych"
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: "r\xFCckl\xE92020adapterdrop"
citations: 128
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.11918'}]
tags: ["EMNLP", "Model Architecture", "Training Techniques"]
short_authors: "R\xFCckl\xE9 et al."
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