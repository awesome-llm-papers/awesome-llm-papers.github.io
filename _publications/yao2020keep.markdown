---
layout: publication
title: 'Keep CALM And Explore: Language Models For Action Generation In Text-based
  Games'
authors: Shunyu Yao, Rohan Rao, Matthew Hausknecht, Karthik Narasimhan
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: yao2020keep
citations: 62
additional_links: [{name: Code, url: 'https://github.com/princeton-nlp/calm-textgame'},
  {name: Paper, url: 'https://arxiv.org/abs/2010.02903'}]
tags: ["EMNLP"]
short_authors: Yao et al.
---
Text-based games present a unique challenge for autonomous agents to operate
in natural language and handle enormous action spaces. In this paper, we
propose the Contextual Action Language Model (CALM) to generate a compact set
of action candidates at each game state. Our key insight is to train language
models on human gameplay, where people demonstrate linguistic priors and a
general game sense for promising actions conditioned on game history. We
combine CALM with a reinforcement learning agent which re-ranks the generated
action candidates to maximize in-game rewards. We evaluate our approach using
the Jericho benchmark, on games unseen by CALM during training. Our method
obtains a 69% relative improvement in average game score over the previous
state-of-the-art model. Surprisingly, on half of these games, CALM is
competitive with or better than other models that have access to ground truth
admissible actions. Code and data are available at
https://github.com/princeton-nlp/calm-textgame.