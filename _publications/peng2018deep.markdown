---
layout: publication
title: 'Deep Dyna-q: Integrating Planning For Task-completion Dialogue Policy Learning'
authors: Baolin Peng, Xiujun Li, Jianfeng Gao, Jingjing Liu, Kam-fai Wong, Shang-yu
  Su
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2018
bibkey: peng2018deep
citations: 169
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1801.06176'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Peng et al.
---
Training a task-completion dialogue agent via reinforcement learning (RL) is
costly because it requires many interactions with real users. One common
alternative is to use a user simulator. However, a user simulator usually lacks
the language complexity of human interlocutors and the biases in its design may
tend to degrade the agent. To address these issues, we present Deep Dyna-Q,
which to our knowledge is the first deep RL framework that integrates planning
for task-completion dialogue policy learning. We incorporate into the dialogue
agent a model of the environment, referred to as the world model, to mimic real
user response and generate simulated experience. During dialogue policy
learning, the world model is constantly updated with real user experience to
approach real user behavior, and in turn, the dialogue agent is optimized using
both real experience and simulated experience. The effectiveness of our
approach is demonstrated on a movie-ticket booking task in both simulated and
human-in-the-loop settings.