---
layout: publication
title: Neural Architecture Search With Reinforcement Learning
authors: Zoph Barret, Le Quoc V.
conference: Arxiv
year: 2016
bibkey: zoph2016neural
citations: 3779
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.01578'}]
tags: [Agentic, Evaluation, Model Architecture, Language Modeling, Reinforcement Learning,
  Datasets]
---
Neural networks are powerful and flexible models that work well for many
difficult learning tasks in image, speech and natural language understanding.
Despite their success, neural networks are still hard to design. In this paper,
we use a recurrent network to generate the model descriptions of neural
networks and train this RNN with reinforcement learning to maximize the
expected accuracy of the generated architectures on a validation set. On the
CIFAR-10 dataset, our method, starting from scratch, can design a novel network
architecture that rivals the best human-invented architecture in terms of test
set accuracy. Our CIFAR-10 model achieves a test error rate of 3.65, which is
0.09 percent better and 1.05x faster than the previous state-of-the-art model
that used a similar architectural scheme. On the Penn Treebank dataset, our
model can compose a novel recurrent cell that outperforms the widely-used LSTM
cell, and other state-of-the-art baselines. Our cell achieves a test set
perplexity of 62.4 on the Penn Treebank, which is 3.6 perplexity better than
the previous state-of-the-art model. The cell can also be transferred to the
character language modeling task on PTB and achieves a state-of-the-art
perplexity of 1.214.