---
layout: publication
title: 'The Natural Language Decathlon: Multitask Learning As Question Answering'
authors: Bryan Mccann, Nitish Shirish Keskar, Caiming Xiong, Richard Socher
conference: Arxiv
year: 2018
bibkey: mccann2018natural
citations: 349
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.08730'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Mccann et al.
---
Deep learning has improved performance on many natural language processing
(NLP) tasks individually. However, general NLP models cannot emerge within a
paradigm that focuses on the particularities of a single metric, dataset, and
task. We introduce the Natural Language Decathlon (decaNLP), a challenge that
spans ten tasks: question answering, machine translation, summarization,
natural language inference, sentiment analysis, semantic role labeling,
zero-shot relation extraction, goal-oriented dialogue, semantic parsing, and
commonsense pronoun resolution. We cast all tasks as question answering over a
context. Furthermore, we present a new Multitask Question Answering Network
(MQAN) jointly learns all tasks in decaNLP without any task-specific modules or
parameters in the multitask setting. MQAN shows improvements in transfer
learning for machine translation and named entity recognition, domain
adaptation for sentiment analysis and natural language inference, and zero-shot
capabilities for text classification. We demonstrate that the MQAN's
multi-pointer-generator decoder is key to this success and performance further
improves with an anti-curriculum training strategy. Though designed for
decaNLP, MQAN also achieves state of the art results on the WikiSQL semantic
parsing task in the single-task setting. We also release code for procuring and
processing data, training and evaluating models, and reproducing all
experiments for decaNLP.