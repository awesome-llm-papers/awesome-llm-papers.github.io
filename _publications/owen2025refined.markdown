---
layout: publication
title: A Refined Analysis Of Massive Activations In Llms
authors: Owen et al.
conference: Astronomy &amp; Astrophysics
year: 2025
bibkey: owen2025refined
citations: 151
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.22329'}]
tags: [Training Techniques, Attention Mechanism, Ethics And Bias, Model Architecture,
  Efficiency And Optimization, Quantization]
---
Motivated in part by their relevance for low-precision training and
quantization, massive activations in large language models (LLMs) have recently
emerged as a topic of interest. However, existing analyses are limited in
scope, and generalizability across architectures is unclear. This paper helps
address some of these gaps by conducting an analysis of massive activations
across a broad range of LLMs, including both GLU-based and non-GLU-based
architectures. Our findings challenge several prior assumptions, most
importantly: (1) not all massive activations are detrimental, i.e. suppressing
them does not lead to an explosion of perplexity or a collapse in downstream
task performance; (2) proposed mitigation strategies such as Attention KV bias
are model-specific and ineffective in certain cases. We consequently
investigate novel hybrid mitigation strategies; in particular pairing Target
Variance Rescaling (TVR) with Attention KV bias or Dynamic Tanh (DyT)
successfully balances the mitigation of massive activations with preserved
downstream model performance in the scenarios we investigated. Our code is
available at: https://github.com/bluorion-com/refine_massive_activations.