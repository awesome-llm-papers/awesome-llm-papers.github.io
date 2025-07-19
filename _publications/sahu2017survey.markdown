---
layout: publication
title: Survey Of Reasoning Using Neural Networks
authors: Sahu Amit
conference: Lecture Notes in Computer Science
year: 2017
bibkey: sahu2017survey
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1702.06186'}]
tags: [Training Techniques, Attention Mechanism, Transformer, Model Architecture,
  Survey Paper, Reinforcement Learning]
---
Reason and inference require process as well as memory skills by humans.
Neural networks are able to process tasks like image recognition (better than
humans) but in memory aspects are still limited (by attention mechanism, size).
Recurrent Neural Network (RNN) and it's modified version LSTM are able to solve
small memory contexts, but as context becomes larger than a threshold, it is
difficult to use them. The Solution is to use large external memory. Still, it
poses many challenges like, how to train neural networks for discrete memory
representation, how to describe long term dependencies in sequential data etc.
Most prominent neural architectures for such tasks are Memory networks:
inference components combined with long term memory and Neural Turing Machines:
neural networks using external memory resources. Also, additional techniques
like attention mechanism, end to end gradient descent on discrete memory
representation are needed to support these solutions. Preliminary results of
above neural architectures on simple algorithms (sorting, copying) and Question
Answering (based on story, dialogs) application are comparable with the state
of the art. In this paper, I explain these architectures (in general), the
additional techniques used and the results of their application.