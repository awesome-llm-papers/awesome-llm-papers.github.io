---
layout: publication
title: 'Neural Question Generation From Text: A Preliminary Study'
authors: Qingyu Zhou, Nan Yang, Furu Wei, Chuanqi Tan, Hangbo Bao, Ming Zhou
conference: Lecture Notes in Computer Science
year: 2018
bibkey: zhou2017neural
citations: 334
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1704.01792'}]
tags: ["Datasets"]
short_authors: Zhou et al.
---
Automatic question generation aims to generate questions from a text passage
where the generated questions can be answered by certain sub-spans of the given
passage. Traditional methods mainly use rigid heuristic rules to transform a
sentence into related questions. In this work, we propose to apply the neural
encoder-decoder model to generate meaningful and diverse questions from natural
language sentences. The encoder reads the input text and the answer position,
to produce an answer-aware input representation, which is fed to the decoder to
generate an answer focused question. We conduct a preliminary study on neural
question generation from text with the SQuAD dataset, and the experiment
results show that our method can produce fluent and diverse questions.