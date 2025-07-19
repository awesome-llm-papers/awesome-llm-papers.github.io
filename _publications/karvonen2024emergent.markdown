---
layout: publication
title: Emergent World Models And Latent Variable Estimation In Chess-playing Language
  Models
authors: Karvonen Adam
conference: 'Journal of the Royal Statistical Society Series B: Statistical Methodology'
year: 2024
bibkey: karvonen2024emergent
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.15498'}]
tags: [Training Techniques, GPT, Model Architecture, Reinforcement Learning, Datasets]
---
Language models have shown unprecedented capabilities, sparking debate over
the source of their performance. Is it merely the outcome of learning syntactic
patterns and surface level statistics, or do they extract semantics and a world
model from the text? Prior work by Li et al. investigated this by training a
GPT model on synthetic, randomly generated Othello games and found that the
model learned an internal representation of the board state. We extend this
work into the more complex domain of chess, training on real games and
investigating our model's internal representations using linear probes and
contrastive activations. The model is given no a priori knowledge of the game
and is solely trained on next character prediction, yet we find evidence of
internal representations of board state. We validate these internal
representations by using them to make interventions on the model's activations
and edit its internal board state. Unlike Li et al's prior synthetic dataset
approach, our analysis finds that the model also learns to estimate latent
variables like player skill to better predict the next character. We derive a
player skill vector and add it to the model, improving the model's win rate by
up to 2.6 times.