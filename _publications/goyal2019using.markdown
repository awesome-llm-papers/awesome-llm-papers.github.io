---
layout: publication
title: Using Natural Language For Reward Shaping In Reinforcement Learning
authors: Prasoon Goyal, Scott Niekum, Raymond J. Mooney
conference: Proceedings of the Twenty-Eighth International Joint Conference on Artificial
  Intelligence
year: 2019
bibkey: goyal2019using
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1903.02020'}]
tags: ["IJCAI", "Reinforcement Learning"]
short_authors: Prasoon Goyal, Scott Niekum, Raymond J. Mooney
---
Recent reinforcement learning (RL) approaches have shown strong performance
in complex domains such as Atari games, but are often highly sample
inefficient. A common approach to reduce interaction time with the environment
is to use reward shaping, which involves carefully designing reward functions
that provide the agent intermediate rewards for progress towards the goal.
However, designing appropriate shaping rewards is known to be difficult as well
as time-consuming. In this work, we address this problem by using natural
language instructions to perform reward shaping. We propose the LanguagE-Action
Reward Network (LEARN), a framework that maps free-form natural language
instructions to intermediate rewards based on actions taken by the agent. These
intermediate language-based rewards can seamlessly be integrated into any
standard reinforcement learning algorithm. We experiment with Montezuma's
Revenge from the Atari Learning Environment, a popular benchmark in RL. Our
experiments on a diverse set of 15 tasks demonstrate that, for the same number
of interactions with the environment, language-based rewards lead to successful
completion of the task 60% more often on average, compared to learning without
language.