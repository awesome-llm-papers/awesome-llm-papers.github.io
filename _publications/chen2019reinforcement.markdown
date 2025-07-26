---
layout: publication
title: Reinforcement Learning Based Graph-to-sequence Model For Natural Question Generation
authors: Yu Chen, Lingfei Wu, Mohammed J. Zaki
conference: Arxiv
year: 2019
bibkey: chen2019reinforcement
citations: 74
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.04942'}]
tags: ["Reinforcement Learning"]
short_authors: Yu Chen, Lingfei Wu, Mohammed J. Zaki
---
Natural question generation (QG) aims to generate questions from a passage
and an answer. Previous works on QG either (i) ignore the rich structure
information hidden in text, (ii) solely rely on cross-entropy loss that leads
to issues like exposure bias and inconsistency between train/test measurement,
or (iii) fail to fully exploit the answer information. To address these
limitations, in this paper, we propose a reinforcement learning (RL) based
graph-to-sequence (Graph2Seq) model for QG. Our model consists of a Graph2Seq
generator with a novel Bidirectional Gated Graph Neural Network based encoder
to embed the passage, and a hybrid evaluator with a mixed objective combining
both cross-entropy and RL losses to ensure the generation of syntactically and
semantically valid text. We also introduce an effective Deep Alignment Network
for incorporating the answer information into the passage at both the word and
contextual levels. Our model is end-to-end trainable and achieves new
state-of-the-art scores, outperforming existing methods by a significant margin
on the standard SQuAD benchmark.