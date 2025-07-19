---
layout: publication
title: 'Roformer: Enhanced Transformer With Rotary Position Embedding'
authors: Su et al.
conference: Neurocomputing
year: 2021
bibkey: su2021roformer
citations: 488
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.09864'}]
tags: [RAG, Attention Mechanism, Alt, Evaluation, Transformer, Model Architecture,
  Datasets]
---
Position encoding recently has shown effective in the transformer
architecture. It enables valuable supervision for dependency modeling between
elements at different positions of the sequence. In this paper, we first
investigate various methods to integrate positional information into the
learning process of transformer-based language models. Then, we propose a novel
method named Rotary Position Embedding(RoPE) to effectively leverage the
positional information. Specifically, the proposed RoPE encodes the absolute
position with a rotation matrix and meanwhile incorporates the explicit
relative position dependency in self-attention formulation. Notably, RoPE
enables valuable properties, including the flexibility of sequence length,
decaying inter-token dependency with increasing relative distances, and the
capability of equipping the linear self-attention with relative position
encoding. Finally, we evaluate the enhanced transformer with rotary position
embedding, also called RoFormer, on various long text classification benchmark
datasets. Our experiments show that it consistently overcomes its alternatives.
Furthermore, we provide a theoretical analysis to explain some experimental
results. RoFormer is already integrated into Huggingface:
https://huggingface.co/docs/transformers/model_doc/roformer.