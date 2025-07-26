---
layout: publication
title: Are Transformers Universal Approximators Of Sequence-to-sequence Functions?
authors: Chulhee Yun, Srinadh Bhojanapalli, Ankit Singh Rawat, Sashank J. Reddi, Sanjiv
  Kumar
conference: Arxiv
year: 2019
bibkey: yun2019are
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1912.10077'}]
tags: ["Model Architecture"]
short_authors: Yun et al.
---
Despite the widespread adoption of Transformer models for NLP tasks, the
expressive power of these models is not well-understood. In this paper, we
establish that Transformer models are universal approximators of continuous
permutation equivariant sequence-to-sequence functions with compact support,
which is quite surprising given the amount of shared parameters in these
models. Furthermore, using positional encodings, we circumvent the restriction
of permutation equivariance, and show that Transformer models can universally
approximate arbitrary continuous sequence-to-sequence functions on a compact
domain. Interestingly, our proof techniques clearly highlight the different
roles of the self-attention and the feed-forward layers in Transformers. In
particular, we prove that fixed width self-attention layers can compute
contextual mappings of the input sequences, playing a key role in the universal
approximation property of Transformers. Based on this insight from our
analysis, we consider other simpler alternatives to self-attention layers and
empirically evaluate them.