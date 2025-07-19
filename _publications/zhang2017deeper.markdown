---
layout: publication
title: A Deeper Look At Experience Replay
authors: Zhang Shangtong, Sutton Richard S.
conference: Arxiv
year: 2017
bibkey: zhang2017deeper
citations: 188
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1712.01275'}]
tags: [Reinforcement Learning]
---
Recently experience replay is widely used in various deep reinforcement
learning (RL) algorithms, in this paper we rethink the utility of experience
replay. It introduces a new hyper-parameter, the memory buffer size, which
needs carefully tuning. However unfortunately the importance of this new
hyper-parameter has been underestimated in the community for a long time. In
this paper we did a systematic empirical study of experience replay under
various function representations. We showcase that a large replay buffer can
significantly hurt the performance. Moreover, we propose a simple O(1) method
to remedy the negative influence of a large replay buffer. We showcase its
utility in both simple grid world and challenging domains like Atari games.