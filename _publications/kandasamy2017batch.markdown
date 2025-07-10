---
layout: publication
title: Batch Policy Gradient Methods For Improving Neural Conversation Models
authors: Kirthevasan Kandasamy, Yoram Bachrach, Ryota Tomioka, Daniel Tarlow, David
  Carter
conference: Arxiv
year: 2017
citations: 22
bibkey: kandasamy2017batch
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1702.03334'}]
tags: [Agentic, Reinforcement Learning, Model Architecture]
---
We study reinforcement learning of chatbots with recurrent neural network
architectures when the rewards are noisy and expensive to obtain. For instance,
a chatbot used in automated customer service support can be scored by quality
assurance agents, but this process can be expensive, time consuming and noisy.
Previous reinforcement learning work for natural language processing uses
on-policy updates and/or is designed for on-line learning settings. We
demonstrate empirically that such strategies are not appropriate for this
setting and develop an off-policy batch policy gradient method (BPG). We
demonstrate the efficacy of our method via a series of synthetic experiments
and an Amazon Mechanical Turk experiment on a restaurant recommendations
dataset.