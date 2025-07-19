---
layout: publication
title: Real-time Emotion Recognition Via Attention Gated Hierarchical Memory Network
authors: Jiao Wenxiang, Lyu Michael R., King Irwin
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2019
bibkey: jiao2019real
citations: 126
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.09075'}]
tags: [Attention Mechanism, Model Architecture, Reinforcement Learning, AAAI, Datasets,
  Merging]
---
Real-time emotion recognition (RTER) in conversations is significant for
developing emotionally intelligent chatting machines. Without the future
context in RTER, it becomes critical to build the memory bank carefully for
capturing historical context and summarize the memories appropriately to
retrieve relevant information. We propose an Attention Gated Hierarchical
Memory Network (AGHMN) to address the problems of prior work: (1) Commonly used
convolutional neural networks (CNNs) for utterance feature extraction are less
compatible in the memory modules; (2) Unidirectional gated recurrent units
(GRUs) only allow each historical utterance to have context before it,
preventing information propagation in the opposite direction; (3) The Soft
Attention for summarizing loses the positional and ordering information of
memories, regardless of how the memory bank is built. Particularly, we propose
a Hierarchical Memory Network (HMN) with a bidirectional GRU (BiGRU) as the
utterance reader and a BiGRU fusion layer for the interaction between
historical utterances. For memory summarizing, we propose an Attention GRU
(AGRU) where we utilize the attention weights to update the internal state of
GRU. We further promote the AGRU to a bidirectional variant (BiAGRU) to balance
the contextual information from recent memories and that from distant memories.
We conduct experiments on two emotion conversation datasets with extensive
analysis, demonstrating the efficacy of our AGHMN models.