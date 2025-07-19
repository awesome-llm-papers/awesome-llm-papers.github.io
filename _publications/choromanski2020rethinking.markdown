---
layout: publication
title: Rethinking Attention With Performers
authors: Choromanski et al.
conference: Arxiv
year: 2020
bibkey: choromanski2020rethinking
citations: 381
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.14794'}]
tags: [RAG, Attention Mechanism, Ethics And Bias, Transformer, Model Architecture,
  Time Series, Reinforcement Learning]
---
We introduce Performers, Transformer architectures which can estimate regular
(softmax) full-rank-attention Transformers with provable accuracy, but using
only linear (as opposed to quadratic) space and time complexity, without
relying on any priors such as sparsity or low-rankness. To approximate softmax
attention-kernels, Performers use a novel Fast Attention Via positive
Orthogonal Random features approach (FAVOR+), which may be of independent
interest for scalable kernel methods. FAVOR+ can be also used to efficiently
model kernelizable attention mechanisms beyond softmax. This representational
power is crucial to accurately compare softmax with other kernels for the first
time on large-scale tasks, beyond the reach of regular Transformers, and
investigate optimal attention-kernels. Performers are linear architectures
fully compatible with regular Transformers and with strong theoretical
guarantees: unbiased or nearly-unbiased estimation of the attention matrix,
uniform convergence and low estimation variance. We tested Performers on a rich
set of tasks stretching from pixel-prediction through text models to protein
sequence modeling. We demonstrate competitive results with other examined
efficient sparse and dense attention methods, showcasing effectiveness of the
novel attention-learning paradigm leveraged by Performers.