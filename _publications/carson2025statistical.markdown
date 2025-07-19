---
layout: publication
title: A Statistical Physics Of Language Model Reasoning
authors: Carson Jack David, Reisizadeh Amir
conference: 'Journal of Statistical Mechanics: Theory and Experiment'
year: 2025
bibkey: carson2025statistical
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.04374'}]
tags: [Tools, Evaluation, Transformer, Model Architecture, Datasets, Merging]
---
Transformer LMs show emergent reasoning that resists mechanistic understanding. We offer a statistical physics framework for continuous-time chain-of-thought reasoning dynamics. We model sentence-level hidden state trajectories as a stochastic dynamical system on a lower-dimensional manifold. This drift-diffusion system uses latent regime switching to capture diverse reasoning phases, including misaligned states or failures. Empirical trajectories (8 models, 7 benchmarks) show a rank-40 projection (balancing variance capture and feasibility) explains ~50% variance. We find four latent reasoning regimes. An SLDS model is formulated and validated to capture these features. The framework enables low-cost reasoning simulation, offering tools to study and predict critical transitions like misaligned states or other LM failures.