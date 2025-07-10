---
layout: publication
title: 'RWKV: Reinventing Rnns For The Transformer Era'
authors: Bo Peng et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2023
citations: 107
bibkey: peng2023reinventing
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2305.13048v2'}]
tags: [Model Architecture, Attention Mechanism, Transformer, RAG, Reinforcement Learning,
  Efficiency and Optimization, Training Techniques, Large-Scale Training]
---
Transformers have revolutionized almost all natural language processing (NLP)
tasks but suffer from memory and computational complexity that scales
quadratically with sequence length. In contrast, recurrent neural networks
(RNNs) exhibit linear scaling in memory and computational requirements but
struggle to match the same performance as Transformers due to limitations in
parallelization and scalability. We propose a novel model architecture,
Receptance Weighted Key Value (RWKV), that combines the efficient
parallelizable training of transformers with the efficient inference of RNNs.
  Our approach leverages a linear attention mechanism and allows us to
formulate the model as either a Transformer or an RNN, thus parallelizing
computations during training and maintains constant computational and memory
complexity during inference. We scale our models as large as 14 billion
parameters, by far the largest dense RNN ever trained, and find RWKV performs
on par with similarly sized Transformers, suggesting future work can leverage
this architecture to create more efficient models. This work presents a
significant step towards reconciling trade-offs between computational
efficiency and model performance in sequence processing tasks.