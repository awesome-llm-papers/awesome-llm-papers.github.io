---
layout: publication
title: 'Fast Transformer Decoding: One Write-head Is All You Need'
authors: Shazeer Noam
conference: Arxiv
year: 2019
bibkey: shazeer2019fast
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.02150'}]
tags: [Training Techniques, Attention Mechanism, Alt, Transformer, Model Architecture]
---
Multi-head attention layers, as used in the Transformer neural sequence
model, are a powerful alternative to RNNs for moving information across and
between sequences. While training these layers is generally fast and simple,
due to parallelizability across the length of the sequence, incremental
inference (where such paralleization is impossible) is often slow, due to the
memory-bandwidth cost of repeatedly loading the large "keys" and "values"
tensors. We propose a variant called multi-query attention, where the keys and
values are shared across all of the different attention "heads", greatly
reducing the size of these tensors and hence the memory bandwidth requirements
of incremental decoding. We verify experimentally that the resulting models can
indeed be much faster to decode, and incur only minor quality degradation from
the baseline.