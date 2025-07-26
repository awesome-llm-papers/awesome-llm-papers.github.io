---
layout: publication
title: Using Pre-trained Models To Boost Code Review Automation
authors: Rosalia Tufano, Simone Masiero, Antonio Mastropaolo, Luca Pascarella, Denys
  Poshyvanyk, Gabriele Bavota
conference: Proceedings of the 44th International Conference on Software Engineering
year: 2022
bibkey: tufano2022using
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2201.06850'}]
tags: ["Llm For Code"]
short_authors: Tufano et al.
---
Code review is a practice widely adopted in open source and industrial
projects. Given the non-negligible cost of such a process, researchers started
investigating the possibility of automating specific code review tasks. We
recently proposed Deep Learning (DL) models targeting the automation of two
tasks: the first model takes as input a code submitted for review and
implements in it changes likely to be recommended by a reviewer; the second
takes as input the submitted code and a reviewer comment posted in natural
language and automatically implements the change required by the reviewer.
While the preliminary results we achieved are encouraging, both models had been
tested in rather simple code review scenarios, substantially simplifying the
targeted problem. This was also due to the choices we made when designing both
the technique and the experiments. In this paper, we build on top of that work
by demonstrating that a pre-trained Text-To-Text Transfer Transformer (T5)
model can outperform previous DL models for automating code review tasks. Also,
we conducted our experiments on a larger and more realistic (and challenging)
dataset of code review activities.