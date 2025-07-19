---
layout: publication
title: Improving Conditional Sequence Generative Adversarial Networks By Stepwise
  Evaluation
authors: Tuan Yi-lin, Lee Hung-yi
conference: IEEE/ACM Transactions on Audio, Speech, and Language Processing
year: 2018
bibkey: tuan2018improving
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.05599'}]
tags: [Training Techniques, Reinforcement Learning, Evaluation, Security]
---
Sequence generative adversarial networks (SeqGAN) have been used to improve
conditional sequence generation tasks, for example, chit-chat dialogue
generation. To stabilize the training of SeqGAN, Monte Carlo tree search (MCTS)
or reward at every generation step (REGS) is used to evaluate the goodness of a
generated subsequence. MCTS is computationally intensive, but the performance
of REGS is worse than MCTS. In this paper, we propose stepwise GAN (StepGAN),
in which the discriminator is modified to automatically assign scores
quantifying the goodness of each subsequence at every generation step. StepGAN
has significantly less computational costs than MCTS. We demonstrate that
StepGAN outperforms previous GAN-based methods on both synthetic experiment and
chit-chat dialogue generation.