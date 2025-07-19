---
layout: publication
title: A Practical Survey On Faster And Lighter Transformers
authors: "Fournier Quentin, Caron Ga\xE9tan Marceau, Aloise Daniel"
conference: ACM Computing Surveys
year: 2021
bibkey: fournier2021practical
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.14636'}]
tags: [Interpretability And Explainability, Attention Mechanism, Distillation, Alt,
  Transformer, Model Architecture, Efficiency And Optimization, Survey Paper, Reinforcement
    Learning, Pruning]
---
Recurrent neural networks are effective models to process sequences. However,
they are unable to learn long-term dependencies because of their inherent
sequential nature. As a solution, Vaswani et al. introduced the Transformer, a
model solely based on the attention mechanism that is able to relate any two
positions of the input sequence, hence modelling arbitrary long dependencies.
The Transformer has improved the state-of-the-art across numerous sequence
modelling tasks. However, its effectiveness comes at the expense of a quadratic
computational and memory complexity with respect to the sequence length,
hindering its adoption. Fortunately, the deep learning community has always
been interested in improving the models' efficiency, leading to a plethora of
solutions such as parameter sharing, pruning, mixed-precision, and knowledge
distillation. Recently, researchers have directly addressed the Transformer's
limitation by designing lower-complexity alternatives such as the Longformer,
Reformer, Linformer, and Performer. However, due to the wide range of
solutions, it has become challenging for researchers and practitioners to
determine which methods to apply in practice in order to meet the desired
trade-off between capacity, computation, and memory. This survey addresses this
issue by investigating popular approaches to make Transformers faster and
lighter and by providing a comprehensive explanation of the methods' strengths,
limitations, and underlying assumptions.