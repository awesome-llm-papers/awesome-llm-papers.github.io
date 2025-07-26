---
layout: publication
title: Flexible End-to-end Dialogue System For Knowledge Grounded Conversation
authors: Wenya Zhu, Kaixiang Mo, Yu Zhang, Zhangbin Zhu, Xuezheng Peng, Qiang Yang
conference: Arxiv
year: 2017
bibkey: zhu2017flexible
citations: 89
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1709.04264'}]
tags: []
short_authors: Zhu et al.
---
In knowledge grounded conversation, domain knowledge plays an important role
in a special domain such as Music. The response of knowledge grounded
conversation might contain multiple answer entities or no entity at all.
Although existing generative question answering (QA) systems can be applied to
knowledge grounded conversation, they either have at most one entity in a
response or cannot deal with out-of-vocabulary entities. We propose a fully
data-driven generative dialogue system GenDS that is capable of generating
responses based on input message and related knowledge base (KB). To generate
arbitrary number of answer entities even when these entities never appear in
the training set, we design a dynamic knowledge enquirer which selects
different answer entities at different positions in a single response,
according to different local context. It does not rely on the representations
of entities, enabling our model deal with out-of-vocabulary entities. We
collect a human-human conversation data (ConversMusic) with knowledge
annotations. The proposed method is evaluated on CoversMusic and a public
question answering dataset. Our proposed GenDS system outperforms baseline
methods significantly in terms of the BLEU, entity accuracy, entity recall and
human evaluation. Moreover,the experiments also demonstrate that GenDS works
better even on small datasets.