---
layout: publication
title: Simultaneous Translation With Flexible Policy Via Restricted Imitation Learning
authors: Zheng et al.
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: zheng2019simultaneous
citations: 74
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.01135'}]
tags: [Agentic, Reinforcement Learning, ACL, Training Techniques]
---
Simultaneous translation is widely useful but remains one of the most
difficult tasks in NLP. Previous work either uses fixed-latency policies, or
train a complicated two-staged model using reinforcement learning. We propose a
much simpler single model that adds a `delay' token to the target vocabulary,
and design a restricted dynamic oracle to greatly simplify training.
Experiments on Chinese<->English simultaneous translation show that our work
leads to flexible policies that achieve better BLEU scores and lower latencies
compared to both fixed and RL-learned policies.