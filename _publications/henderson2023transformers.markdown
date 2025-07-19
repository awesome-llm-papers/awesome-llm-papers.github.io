---
layout: publication
title: Transformers As Graph-to-graph Models
authors: Henderson et al.
conference: Chemical Science
year: 2023
bibkey: henderson2023transformers
citations: 374
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.17936'}]
tags: [Training Techniques, Attention Mechanism, GPT, Transformer, Model Architecture]
---
We argue that Transformers are essentially graph-to-graph models, with
sequences just being a special case. Attention weights are functionally
equivalent to graph edges. Our Graph-to-Graph Transformer architecture makes
this ability explicit, by inputting graph edges into the attention weight
computations and predicting graph edges with attention-like functions, thereby
integrating explicit graphs into the latent graphs learned by pretrained
Transformers. Adding iterative graph refinement provides a joint embedding of
input, output, and latent graphs, allowing non-autoregressive graph prediction
to optimise the complete graph without any bespoke pipeline or decoding
strategy. Empirical results show that this architecture achieves
state-of-the-art accuracies for modelling a variety of linguistic structures,
integrating very effectively with the latent linguistic representations learned
by pretraining.