---
layout: publication
title: Imitating Language Via Scalable Inverse Reinforcement Learning
authors: Wulfmeier et al.
conference: Twenty-first international conference on Machine learning  - ICML '04
year: 2024
bibkey: wulfmeier2024imitating
citations: 1410
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.01369'}]
tags: [Training Techniques, GPT, Alt, Agentic, ICML, Reinforcement Learning, Fine
    Tuning, Datasets]
---
The majority of language model training builds on imitation learning. It
covers pretraining, supervised fine-tuning, and affects the starting conditions
for reinforcement learning from human feedback (RLHF). The simplicity and
scalability of maximum likelihood estimation (MLE) for next token prediction
led to its role as predominant paradigm. However, the broader field of
imitation learning can more effectively utilize the sequential structure
underlying autoregressive generation. We focus on investigating the inverse
reinforcement learning (IRL) perspective to imitation, extracting rewards and
directly optimizing sequences instead of individual token likelihoods and
evaluate its benefits for fine-tuning large language models. We provide a new
angle, reformulating inverse soft-Q-learning as a temporal difference
regularized extension of MLE. This creates a principled connection between MLE
and IRL and allows trading off added complexity with increased performance and
diversity of generations in the supervised fine-tuning (SFT) setting. We find
clear advantages for IRL-based imitation, in particular for retaining diversity
while maximizing task performance, rendering IRL a strong alternative on fixed
SFT datasets even without online data generation. Our analysis of IRL-extracted
reward functions further indicates benefits for more robust reward functions
via tighter integration of supervised and preference-based LLM post-training.