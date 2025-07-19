---
layout: publication
title: 'Time To Take Emoji Seriously: They Vastly Improve Casual Conversational Models'
authors: Delobelle Pieter, Berendt Bettina
conference: BMJ
year: 2019
bibkey: delobelle2019time
citations: 105
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.13793'}]
tags: [Model Architecture, Reinforcement Learning, Datasets, BERT]
---
Graphical emoji are ubiquitous in modern-day online conversations. So is a
single thumbs-up emoji able to signify an agreement, without any words. We
argue that the current state-of-the-art systems are ill-equipped to correctly
interpret these emoji, especially in a conversational context. However, in a
casual context, the benefits might be high: a better understanding of users'
utterances and more natural, emoji-rich responses.
  With this in mind, we modify BERT to fully support emoji, both from the
Unicode Standard and custom emoji. This modified BERT is then trained on a
corpus of question-answer (QA) tuples with a high number of emoji, where we're
able to increase the 1-of-100 accuracy from 12.7% for the current
state-of-the-art to 17.8% for our model with emoji support.