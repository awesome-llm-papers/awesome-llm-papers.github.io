---
layout: publication
title: 'Qronos: Correcting The Past By Shaping The Future... In Post-training Quantization'
authors: Zhang et al.
conference: Machine Learning
year: 2025
bibkey: zhang2025qronos
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.11695'}]
tags: [Training Techniques, GPT, Alt, Tools, ICML, Efficiency And Optimization, Quantization,
  Merging]
---
We introduce Qronos -- a new state-of-the-art post-training quantization algorithm that sequentially rounds and updates neural network weights. Qronos not only explicitly corrects errors due to both weight and activation quantization, but also errors resulting from quantizing previous layers. Our iterative algorithm is based on an interpretable and disciplined optimization framework that subsumes and surpasses existing data-driven approaches. At each step, Qronos alternates between error correction and diffusion via optimal update rules. Importantly, we prove that Qronos admits an efficient implementation that uses the Cholesky decomposition for solving least-squares problems. We also demonstrate that Qronos is compatible with existing transformation techniques such as Hadamard-based incoherence processing and weight-activation scaling equalization, among others. We evaluate Qronos using recent autoregressive language generation models in the Llama3 family; Qronos consistently outperforms previous state-of-the-art adaptive rounding methods when quantizing the weights, activations, and/or KV caches.