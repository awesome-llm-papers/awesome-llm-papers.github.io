---
layout: publication
title: 'Sequential Matching Network: A New Architecture For Multi-turn Response Selection
  In Retrieval-based Chatbots'
authors: Yu Wu, Wei Wu, Chen Xing, Ming Zhou, Zhoujun Li
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: wu2016sequential
citations: 550
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1612.01627'}]
tags: ["Model Architecture"]
short_authors: Wu et al.
---
We study response selection for multi-turn conversation in retrieval-based
chatbots. Existing work either concatenates utterances in context or matches a
response with a highly abstract context vector finally, which may lose
relationships among utterances or important contextual information. We propose
a sequential matching network (SMN) to address both problems. SMN first matches
a response with each utterance in the context on multiple levels of
granularity, and distills important matching information from each pair as a
vector with convolution and pooling operations. The vectors are then
accumulated in a chronological order through a recurrent neural network (RNN)
which models relationships among utterances. The final matching score is
calculated with the hidden states of the RNN. An empirical study on two public
data sets shows that SMN can significantly outperform state-of-the-art methods
for response selection in multi-turn conversation.