---
layout: publication
title: Selective Experience Replay For Lifelong Learning
authors: Isele David, Cosgun Akansel
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2018
bibkey: isele2018selective
citations: 295
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1802.10269'}]
tags: [RAG, Training Techniques, Agentic, Reinforcement Learning, AAAI]
---
Deep reinforcement learning has emerged as a powerful tool for a variety of
learning tasks, however deep nets typically exhibit forgetting when learning
multiple tasks in sequence. To mitigate forgetting, we propose an experience
replay process that augments the standard FIFO buffer and selectively stores
experiences in a long-term memory. We explore four strategies for selecting
which experiences will be stored: favoring surprise, favoring reward, matching
the global training distribution, and maximizing coverage of the state space.
We show that distribution matching successfully prevents catastrophic
forgetting, and is consistently the best approach on all domains tested. While
distribution matching has better and more consistent performance, we identify
one case in which coverage maximization is beneficial - when tasks that receive
less trained are more important. Overall, our results show that selective
experience replay, when suitable selection algorithms are employed, can prevent
catastrophic forgetting.