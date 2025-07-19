---
layout: publication
title: 'Playing The Lottery With Rewards And Multiple Languages: Lottery Tickets In
  RL And NLP'
authors: Yu et al.
conference: Arxiv
year: 2019
bibkey: yu2019playing
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.02768'}]
tags: [Training Techniques, Agentic, Transformer, Model Architecture, Efficiency And
    Optimization, Reinforcement Learning, Pruning]
---
The lottery ticket hypothesis proposes that over-parameterization of deep
neural networks (DNNs) aids training by increasing the probability of a "lucky"
sub-network initialization being present rather than by helping the
optimization process (Frankle & Carbin, 2019). Intriguingly, this phenomenon
suggests that initialization strategies for DNNs can be improved substantially,
but the lottery ticket hypothesis has only previously been tested in the
context of supervised learning for natural image tasks. Here, we evaluate
whether "winning ticket" initializations exist in two different domains:
natural language processing (NLP) and reinforcement learning (RL).For NLP, we
examined both recurrent LSTM models and large-scale Transformer models (Vaswani
et al., 2017). For RL, we analyzed a number of discrete-action space tasks,
including both classic control and pixel control. Consistent with workin
supervised image classification, we confirm that winning ticket initializations
generally outperform parameter-matched random initializations, even at extreme
pruning rates for both NLP and RL. Notably, we are able to find winning ticket
initializations for Transformers which enable models one-third the size to
achieve nearly equivalent performance. Together, these results suggest that the
lottery ticket hypothesis is not restricted to supervised learning of natural
images, but rather represents a broader phenomenon in DNNs.