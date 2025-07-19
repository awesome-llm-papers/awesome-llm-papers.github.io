---
layout: publication
title: A Constraint-enforcing Reward For Adversarial Attacks On Text Classifiers
authors: Roth et al.
conference: ICASSP 2019 - 2019 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2024
bibkey: roth2024constraint
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.11904'}]
tags: [Training Techniques, Alt, Agentic, ICASSP, Reinforcement Learning, Security,
  Fine Tuning, Datasets]
---
Text classifiers are vulnerable to adversarial examples --
correctly-classified examples that are deliberately transformed to be
misclassified while satisfying acceptability constraints. The conventional
approach to finding adversarial examples is to define and solve a combinatorial
optimisation problem over a space of allowable transformations. While
effective, this approach is slow and limited by the choice of transformations.
An alternate approach is to directly generate adversarial examples by
fine-tuning a pre-trained language model, as is commonly done for other
text-to-text tasks. This approach promises to be much quicker and more
expressive, but is relatively unexplored. For this reason, in this work we
train an encoder-decoder paraphrase model to generate a diverse range of
adversarial examples. For training, we adopt a reinforcement learning algorithm
and propose a constraint-enforcing reward that promotes the generation of valid
adversarial examples. Experimental results over two text classification
datasets show that our model has achieved a higher success rate than the
original paraphrase model, and overall has proved more effective than other
competitive attacks. Finally, we show how key design choices impact the
generated examples and discuss the strengths and weaknesses of the proposed
approach.