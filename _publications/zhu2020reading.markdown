---
layout: publication
title: 'DUMA: Reading Comprehension With Transposition Thinking'
authors: Pengfei Zhu, Hai Zhao, Xiaoguang Li
conference: IEEE/ACM Transactions on Audio, Speech, and Language Processing
year: 2020
citations: 30
bibkey: zhu2020reading
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2001.09415'}]
tags: [Reinforcement Learning, Model Architecture, Attention Mechanism, Evaluation]
---
Multi-choice Machine Reading Comprehension (MRC) requires model to decide the
correct answer from a set of answer options when given a passage and a
question. Thus in addition to a powerful Pre-trained Language Model (PrLM) as
encoder, multi-choice MRC especially relies on a matching network design which
is supposed to effectively capture the relationships among the triplet of
passage, question and answers. While the newer and more powerful PrLMs have
shown their mightiness even without the support from a matching network, we
propose a new DUal Multi-head Co-Attention (DUMA) model, which is inspired by
human's transposition thinking process solving the multi-choice MRC problem:
respectively considering each other's focus from the standpoint of passage and
question. The proposed DUMA has been shown effective and is capable of
generally promoting PrLMs. Our proposed method is evaluated on two benchmark
multi-choice MRC tasks, DREAM and RACE, showing that in terms of powerful
PrLMs, DUMA can still boost the model to reach new state-of-the-art
performance.