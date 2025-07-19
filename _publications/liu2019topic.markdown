---
layout: publication
title: Topic-aware Pointer-generator Networks For Summarizing Spoken Conversations
authors: Liu et al.
conference: 2019 IEEE Automatic Speech Recognition and Understanding Workshop (ASRU)
year: 2019
bibkey: liu2019topic
citations: 89
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.01335'}]
tags: [Attention Mechanism, ASRU, Model Architecture, Reinforcement Learning, Merging]
---
Due to the lack of publicly available resources, conversation summarization
has received far less attention than text summarization. As the purpose of
conversations is to exchange information between at least two interlocutors,
key information about a certain topic is often scattered and spanned across
multiple utterances and turns from different speakers. This phenomenon is more
pronounced during spoken conversations, where speech characteristics such as
backchanneling and false-starts might interrupt the topical flow. Moreover,
topic diffusion and (intra-utterance) topic drift are also more common in
human-to-human conversations. Such linguistic characteristics of dialogue
topics make sentence-level extractive summarization approaches used in spoken
documents ill-suited for summarizing conversations. Pointer-generator networks
have effectively demonstrated its strength at integrating extractive and
abstractive capabilities through neural modeling in text summarization. To the
best of our knowledge, to date no one has adopted it for summarizing
conversations. In this work, we propose a topic-aware architecture to exploit
the inherent hierarchical structure in conversations to further adapt the
pointer-generator model. Our approach significantly outperforms competitive
baselines, achieves more efficient learning outcomes, and attains more robust
performance.