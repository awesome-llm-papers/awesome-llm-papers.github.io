---
layout: publication
title: Hardware-aware Training For Large-scale And Diverse Deep Learning Inference
  Workloads Using In-memory Computing-based Accelerators
authors: Rasch et al.
conference: Nature Communications
year: 2023
bibkey: rasch2023hardware
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.08469'}]
tags: [Training Techniques, Transformer, Model Architecture, Reinforcement Learning,
  Security]
---
Analog in-memory computing (AIMC) -- a promising approach for
energy-efficient acceleration of deep learning workloads -- computes
matrix-vector multiplications (MVMs) but only approximately, due to
nonidealities that often are non-deterministic or nonlinear. This can adversely
impact the achievable deep neural network (DNN) inference accuracy as compared
to a conventional floating point (FP) implementation. While retraining has
previously been suggested to improve robustness, prior work has explored only a
few DNN topologies, using disparate and overly simplified AIMC hardware models.
Here, we use hardware-aware (HWA) training to systematically examine the
accuracy of AIMC for multiple common artificial intelligence (AI) workloads
across multiple DNN topologies, and investigate sensitivity and robustness to a
broad set of nonidealities. By introducing a new and highly realistic AIMC
crossbar-model, we improve significantly on earlier retraining approaches. We
show that many large-scale DNNs of various topologies, including convolutional
neural networks (CNNs), recurrent neural networks (RNNs), and transformers, can
in fact be successfully retrained to show iso-accuracy on AIMC. Our results
further suggest that AIMC nonidealities that add noise to the inputs or
outputs, not the weights, have the largest impact on DNN accuracy, and that
RNNs are particularly robust to all nonidealities.