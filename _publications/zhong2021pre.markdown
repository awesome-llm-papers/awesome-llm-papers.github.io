---
layout: publication
title: 'Dialoglm: Pre-trained Model For Long Dialogue Understanding And Summarization'
authors: Ming Zhong, Yang Liu, Yichong Xu, Chenguang Zhu, Michael Zeng
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
citations: 32
bibkey: zhong2021pre
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.02492'}, {name: Code,
    url: 'https://github.com/microsoft/DialogLM)'}]
tags: [Has Code, Model Architecture, Attention Mechanism, Tools, Reinforcement Learning,
  Pre-Training, Training Techniques]
---
Dialogue is an essential part of human communication and cooperation.
Existing research mainly focuses on short dialogue scenarios in a one-on-one
fashion. However, multi-person interactions in the real world, such as meetings
or interviews, are frequently over a few thousand words. There is still a lack
of corresponding research and powerful tools to understand and process such
long dialogues. Therefore, in this work, we present a pre-training framework
for long dialogue understanding and summarization. Considering the nature of
long conversations, we propose a window-based denoising approach for generative
pre-training. For a dialogue, it corrupts a window of text with
dialogue-inspired noise, and guides the model to reconstruct this window based
on the content of the remaining conversation. Furthermore, to process longer
input, we augment the model with sparse attention which is combined with
conventional attention in a hybrid manner. We conduct extensive experiments on
five datasets of long dialogues, covering tasks of dialogue summarization,
abstractive question answering and topic segmentation. Experimentally, we show
that our pre-trained model DialogLM significantly surpasses the
state-of-the-art models across datasets and tasks. Source code and all the
pre-trained models are available on our GitHub repository
(https://github.com/microsoft/DialogLM).