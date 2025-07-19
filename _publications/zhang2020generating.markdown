---
layout: publication
title: Generating Fluent Adversarial Examples For Natural Languages
authors: Zhang et al.
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: zhang2020generating
citations: 102
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.06174'}]
tags: [Security, ACL, Training Techniques]
---
Efficiently building an adversarial attacker for natural language processing
(NLP) tasks is a real challenge. Firstly, as the sentence space is discrete, it
is difficult to make small perturbations along the direction of gradients.
Secondly, the fluency of the generated examples cannot be guaranteed. In this
paper, we propose MHA, which addresses both problems by performing
Metropolis-Hastings sampling, whose proposal is designed with the guidance of
gradients. Experiments on IMDB and SNLI show that our proposed MHA outperforms
the baseline model on attacking capability. Adversarial training with MAH also
leads to better robustness and performance.