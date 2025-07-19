---
layout: publication
title: 'Transformers Get Stable: An End-to-end Signal Propagation Theory For Language
  Models'
authors: Kedia et al.
conference: Lecture Notes in Computer Science
year: 2024
bibkey: kedia2024transformers
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.09635'}]
tags: [Training Techniques, Attention Mechanism, Tools, Transformer, Model Architecture,
  Language Modeling, Security, Datasets]
---
In spite of their huge success, transformer models remain difficult to scale
in depth. In this work, we develop a unified signal propagation theory and
provide formulae that govern the moments of the forward and backward signal
through the transformer model. Our framework can be used to understand and
mitigate vanishing/exploding gradients, rank collapse, and instability
associated with high attention scores. We also propose DeepScaleLM, an
initialization and scaling scheme that conserves unit output/gradient moments
throughout the model, enabling the training of very deep models with 1000
layers. We find that transformer models could be much deeper - our deep models
with fewer parameters outperform shallow models in Language Modeling, Speech
Translation, and Image Classification, across encoder-only, decoder-only and
encoder-decoder variants, for both Pre-LN and Post-LN transformers, for
multiple datasets and model sizes. These improvements also translate into
improved performance on downstream Question Answering tasks and improved
robustness for Image Classification.