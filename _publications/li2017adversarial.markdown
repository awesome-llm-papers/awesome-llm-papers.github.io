---
layout: publication
title: Adversarial Learning For Neural Dialogue Generation
authors: "Jiwei Li, Will Monroe, Tianlin Shi, S\xE9bastien Jean, Alan Ritter, Dan\
  \ Jurafsky"
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: li2017adversarial
citations: 796
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1701.06547'}]
tags: ["Evaluation", "Reinforcement Learning", "Training Techniques"]
short_authors: Li et al.
---
In this paper, drawing intuition from the Turing test, we propose using
adversarial training for open-domain dialogue generation: the system is trained
to produce sequences that are indistinguishable from human-generated dialogue
utterances. We cast the task as a reinforcement learning (RL) problem where we
jointly train two systems, a generative model to produce response sequences,
and a discriminator---analagous to the human evaluator in the Turing test--- to
distinguish between the human-generated dialogues and the machine-generated
ones. The outputs from the discriminator are then used as rewards for the
generative model, pushing the system to generate dialogues that mostly resemble
human dialogues.
  In addition to adversarial training we describe a model for adversarial \{\em
evaluation\} that uses success in fooling an adversary as a dialogue evaluation
metric, while avoiding a number of potential pitfalls. Experimental results on
several metrics, including adversarial evaluation, demonstrate that the
adversarially-trained system generates higher-quality responses than previous
baselines.