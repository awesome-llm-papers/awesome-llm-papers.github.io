---
layout: publication
title: A Simple Language Model For Task-oriented Dialogue
authors: Ehsan Hosseini-asl, Bryan Mccann, Chien-sheng Wu, Semih Yavuz, Richard Socher
conference: Arxiv
year: 2020
bibkey: hosseiniasl2020simple
citations: 263
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00796'}]
tags: ["Model Architecture"]
short_authors: Hosseini-asl et al.
---
Task-oriented dialogue is often decomposed into three tasks: understanding
user input, deciding actions, and generating a response. While such
decomposition might suggest a dedicated model for each sub-task, we find a
simple, unified approach leads to state-of-the-art performance on the MultiWOZ
dataset. SimpleTOD is a simple approach to task-oriented dialogue that uses a
single, causal language model trained on all sub-tasks recast as a single
sequence prediction problem. This allows SimpleTOD to fully leverage transfer
learning from pre-trained, open domain, causal language models such as GPT-2.
SimpleTOD improves over the prior state-of-the-art in joint goal accuracy for
dialogue state tracking, and our analysis reveals robustness to noisy
annotations in this setting. SimpleTOD also improves the main metrics used to
evaluate action decisions and response generation in an end-to-end setting:
inform rate by 8.1 points, success rate by 9.7 points, and combined score by
7.2 points.