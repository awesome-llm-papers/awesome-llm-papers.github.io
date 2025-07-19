---
layout: publication
title: Visualizing And Understanding Curriculum Learning For Long Short-term Memory
  Networks
authors: Cirik Volkan, Hovy Eduard, Morency Louis-philippe
conference: 2014 IEEE Spoken Language Technology Workshop (SLT)
year: 2016
bibkey: cirik2016visualizing
citations: 145
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.06204'}]
tags: [Training Techniques, Ethics And Bias, Model Architecture, Reinforcement Learning,
  SLT]
---
Curriculum Learning emphasizes the order of training instances in a
computational learning setup. The core hypothesis is that simpler instances
should be learned early as building blocks to learn more complex ones. Despite
its usefulness, it is still unknown how exactly the internal representation of
models are affected by curriculum learning. In this paper, we study the effect
of curriculum learning on Long Short-Term Memory (LSTM) networks, which have
shown strong competency in many Natural Language Processing (NLP) problems. Our
experiments on sentiment analysis task and a synthetic task similar to sequence
prediction tasks in NLP show that curriculum learning has a positive effect on
the LSTM's internal states by biasing the model towards building constructive
representations i.e. the internal representation at the previous timesteps are
used as building blocks for the final prediction. We also find that smaller
models significantly improves when they are trained with curriculum learning.
Lastly, we show that curriculum learning helps more when the amount of training
data is limited.