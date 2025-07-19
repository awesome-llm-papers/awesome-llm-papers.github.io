---
layout: publication
title: Densely Connected Bidirectional LSTM With Applications To Sentence Classification
authors: Ding et al.
conference: Lecture Notes in Computer Science
year: 2018
bibkey: ding2018densely
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1802.00889'}]
tags: [Datasets, Model Architecture, Evaluation, Applications]
---
Deep neural networks have recently been shown to achieve highly competitive
performance in many computer vision tasks due to their abilities of exploring
in a much larger hypothesis space. However, since most deep architectures like
stacked RNNs tend to suffer from the vanishing-gradient and overfitting
problems, their effects are still understudied in many NLP tasks. Inspired by
this, we propose a novel multi-layer RNN model called densely connected
bidirectional long short-term memory (DC-Bi-LSTM) in this paper, which
essentially represents each layer by the concatenation of its hidden state and
all preceding layers' hidden states, followed by recursively passing each
layer's representation to all subsequent layers. We evaluate our proposed model
on five benchmark datasets of sentence classification. DC-Bi-LSTM with depth up
to 20 can be successfully trained and obtain significant improvements over the
traditional Bi-LSTM with the same or even less parameters. Moreover, our model
has promising performance compared with the state-of-the-art approaches.