---
layout: publication
title: Continual Learning In Task-oriented Dialogue Systems
authors: Andrea Madotto, Zhaojiang Lin, Zhenpeng Zhou, Seungwhan Moon, Paul Crook,
  Bing Liu, Zhou Yu, Eunjoon Cho, Zhiguang Wang
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: madotto2020continual
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.15504'}]
tags: ["EMNLP"]
short_authors: Madotto et al.
---
Continual learning in task-oriented dialogue systems can allow us to add new
domains and functionalities through time without incurring the high cost of a
whole system retraining. In this paper, we propose a continual learning
benchmark for task-oriented dialogue systems with 37 domains to be learned
continuously in four settings, such as intent recognition, state tracking,
natural language generation, and end-to-end. Moreover, we implement and compare
multiple existing continual learning baselines, and we propose a simple yet
effective architectural method based on residual adapters. Our experiments
demonstrate that the proposed architectural method and a simple replay-based
strategy perform comparably well but they both achieve inferior performance to
the multi-task learning baseline, in where all the data are shown at once,
showing that continual learning in task-oriented dialogue systems is a
challenging task. Furthermore, we reveal several trade-offs between different
continual learning methods in term of parameter usage and memory size, which
are important in the design of a task-oriented dialogue system. The proposed
benchmark is released together with several baselines to promote more research
in this direction.