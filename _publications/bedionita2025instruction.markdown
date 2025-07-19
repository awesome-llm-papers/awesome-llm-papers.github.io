---
layout: publication
title: Instruction-guided Autoregressive Neural Network Parameter Generation
authors: Bedionita et al.
conference: Physical Review D
year: 2025
bibkey: bedionita2025instruction
citations: 104
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.02012'}]
tags: [RAG, Training Techniques, GPT, Tools, Model Architecture, Efficiency And Optimization,
  Language Modeling, Fine Tuning, Datasets, Merging]
---
Learning to generate neural network parameters conditioned on task
descriptions and architecture specifications is pivotal for advancing model
adaptability and transfer learning. Existing methods especially those based on
diffusion models suffer from limited scalability to large architectures,
rigidity in handling varying network depths, and disjointed parameter
generation that undermines inter-layer coherence. In this work, we propose IGPG
(Instruction Guided Parameter Generation), an autoregressive framework that
unifies parameter synthesis across diverse tasks and architectures. IGPG
leverages a VQ-VAE and an autoregressive model to generate neural network
parameters, conditioned on task instructions, dataset, and architecture
details. By autoregressively generating neural network weights' tokens, IGPG
ensures inter-layer coherence and enables efficient adaptation across models
and datasets. Operating at the token level, IGPG effectively captures complex
parameter distributions aggregated from a broad spectrum of pretrained models.
Extensive experiments on multiple vision datasets demonstrate that IGPG
consolidates diverse pretrained models into a single, flexible generative
framework. The synthesized parameters achieve competitive or superior
performance relative to state-of-the-art methods, especially in terms of
scalability and efficiency when applied to large architectures. These results
underscore ICPG potential as a powerful tool for pretrained weight retrieval,
model selection, and rapid task-specific fine-tuning.