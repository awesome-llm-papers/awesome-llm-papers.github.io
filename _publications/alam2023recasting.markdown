---
layout: publication
title: Recasting Self-attention With Holographic Reduced Representations
authors: Alam et al.
conference: IEEE Transactions on Neural Networks
year: 2023
bibkey: alam2023recasting
citations: 304
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.19534'}]
tags: [Attention Mechanism, Tools, Evaluation, Transformer, Model Architecture, Datasets]
---
In recent years, self-attention has become the dominant paradigm for sequence
modeling in a variety of domains. However, in domains with very long sequence
lengths the \\(\mathcal\{O\}(T^2)\\) memory and \\(\mathcal\{O\}(T^2 H)\\) compute costs
can make using transformers infeasible. Motivated by problems in malware
detection, where sequence lengths of \\(T \geq 100,000\\) are a roadblock to deep
learning, we re-cast self-attention using the neuro-symbolic approach of
Holographic Reduced Representations (HRR). In doing so we perform the same
high-level strategy of the standard self-attention: a set of queries matching
against a set of keys, and returning a weighted response of the values for each
key. Implemented as a ``Hrrformer'' we obtain several benefits including
\\(\mathcal\{O\}(T H log H)\\) time complexity, \\(\mathcal\{O\}(T H)\\) space complexity,
and convergence in \\(10\times\\) fewer epochs. Nevertheless, the Hrrformer
achieves near state-of-the-art accuracy on LRA benchmarks and we are able to
learn with just a single layer. Combined, these benefits make our Hrrformer the
first viable Transformer for such long malware classification sequences and up
to \\(280\times\\) faster to train on the Long Range Arena benchmark. Code is
available at
https://github.com/NeuromorphicComputationResearchProgram/Hrrformer