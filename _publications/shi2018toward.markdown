---
layout: publication
title: Toward Diverse Text Generation With Inverse Reinforcement Learning
authors: Zhan Shi, Xinchi Chen, Xipeng Qiu, Xuanjing Huang
conference: Proceedings of the Twenty-Seventh International Joint Conference on Artificial
  Intelligence
year: 2018
bibkey: shi2018toward
citations: 86
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.11258'}]
tags: ["IJCAI", "Reinforcement Learning"]
short_authors: Shi et al.
---
Text generation is a crucial task in NLP. Recently, several adversarial
generative models have been proposed to improve the exposure bias problem in
text generation. Though these models gain great success, they still suffer from
the problems of reward sparsity and mode collapse. In order to address these
two problems, in this paper, we employ inverse reinforcement learning (IRL) for
text generation. Specifically, the IRL framework learns a reward function on
training data, and then an optimal policy to maximum the expected total reward.
Similar to the adversarial models, the reward and policy function in IRL are
optimized alternately. Our method has two advantages: (1) the reward function
can produce more dense reward signals. (2) the generation policy, trained by
"entropy regularized" policy gradient, encourages to generate more diversified
texts. Experiment results demonstrate that our proposed method can generate
higher quality texts than the previous methods.