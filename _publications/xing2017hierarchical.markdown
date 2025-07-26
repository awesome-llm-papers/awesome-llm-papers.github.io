---
layout: publication
title: Hierarchical Recurrent Attention Network For Response Generation
authors: Chen Xing, Wei Wu, Yu Wu, Ming Zhou, Yalou Huang, Wei-ying Ma
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2018
bibkey: xing2017hierarchical
citations: 151
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1701.07149'}]
tags: ["AAAI", "Model Architecture"]
short_authors: Xing et al.
---
We study multi-turn response generation in chatbots where a response is
generated according to a conversation context. Existing work has modeled the
hierarchy of the context, but does not pay enough attention to the fact that
words and utterances in the context are differentially important. As a result,
they may lose important information in context and generate irrelevant
responses. We propose a hierarchical recurrent attention network (HRAN) to
model both aspects in a unified framework. In HRAN, a hierarchical attention
mechanism attends to important parts within and among utterances with word
level attention and utterance level attention respectively. With the word level
attention, hidden vectors of a word level encoder are synthesized as utterance
vectors and fed to an utterance level encoder to construct hidden
representations of the context. The hidden vectors of the context are then
processed by the utterance level attention and formed as context vectors for
decoding the response. Empirical studies on both automatic evaluation and human
judgment show that HRAN can significantly outperform state-of-the-art models
for multi-turn response generation.