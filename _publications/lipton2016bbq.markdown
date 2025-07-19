---
layout: publication
title: 'Bbq-networks: Efficient Exploration In Deep Reinforcement Learning For Task-oriented
  Dialogue Systems'
authors: Lipton et al.
conference: Arxiv
year: 2016
bibkey: lipton2016bbq
citations: 105
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1608.05081'}]
tags: [Fine Tuning, Efficiency And Optimization, Agentic, Reinforcement Learning]
---
We present a new algorithm that significantly improves the efficiency of
exploration for deep Q-learning agents in dialogue systems. Our agents explore
via Thompson sampling, drawing Monte Carlo samples from a Bayes-by-Backprop
neural network. Our algorithm learns much faster than common exploration
strategies such as \\(\epsilon\\)-greedy, Boltzmann, bootstrapping, and
intrinsic-reward-based ones. Additionally, we show that spiking the replay
buffer with experiences from just a few successful episodes can make Q-learning
feasible when it might otherwise fail.