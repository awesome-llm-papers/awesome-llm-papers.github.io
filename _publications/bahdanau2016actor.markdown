---
layout: publication
title: An Actor-critic Algorithm For Sequence Prediction
authors: Dzmitry Bahdanau, Philemon Brakel, Kelvin Xu, Anirudh Goyal, Ryan Lowe, Joelle
  Pineau, Aaron Courville, Yoshua Bengio
conference: Arxiv
year: 2016
bibkey: bahdanau2016actor
citations: 326
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1607.07086'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Bahdanau et al.
---
We present an approach to training neural networks to generate sequences
using actor-critic methods from reinforcement learning (RL). Current
log-likelihood training methods are limited by the discrepancy between their
training and testing modes, as models must generate tokens conditioned on their
previous guesses rather than the ground-truth tokens. We address this problem
by introducing a \textit\{critic\} network that is trained to predict the value
of an output token, given the policy of an \textit\{actor\} network. This results
in a training procedure that is much closer to the test phase, and allows us to
directly optimize for a task-specific score such as BLEU. Crucially, since we
leverage these techniques in the supervised learning setting rather than the
traditional RL setting, we condition the critic network on the ground-truth
output. We show that our method leads to improved performance on both a
synthetic task, and for German-English machine translation. Our analysis paves
the way for such methods to be applied in natural language generation tasks,
such as machine translation, caption generation, and dialogue modelling.