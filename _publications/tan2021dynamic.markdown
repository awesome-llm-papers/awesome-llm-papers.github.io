---
layout: publication
title: Dynamic Memory Based Attention Network For Sequential Recommendation
authors: Tan et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
bibkey: tan2021dynamic
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.09269'}]
tags: [Attention Mechanism, Evaluation, Model Architecture, Reinforcement Learning,
  AAAI, Datasets]
---
Sequential recommendation has become increasingly essential in various online
services. It aims to model the dynamic preferences of users from their
historical interactions and predict their next items. The accumulated user
behavior records on real systems could be very long. This rich data brings
opportunities to track actual interests of users. Prior efforts mainly focus on
making recommendations based on relatively recent behaviors. However, the
overall sequential data may not be effectively utilized, as early interactions
might affect users' current choices. Also, it has become intolerable to scan
the entire behavior sequence when performing inference for each user, since
real-world system requires short response time. To bridge the gap, we propose a
novel long sequential recommendation model, called Dynamic Memory-based
Attention Network (DMAN). It segments the overall long behavior sequence into a
series of sub-sequences, then trains the model and maintains a set of memory
blocks to preserve long-term interests of users. To improve memory fidelity,
DMAN dynamically abstracts each user's long-term interest into its own memory
blocks by minimizing an auxiliary reconstruction loss. Based on the dynamic
memory, the user's short-term and long-term interests can be explicitly
extracted and combined for efficient joint recommendation. Empirical results
over four benchmark datasets demonstrate the superiority of our model in
capturing long-term dependency over various state-of-the-art sequential models.