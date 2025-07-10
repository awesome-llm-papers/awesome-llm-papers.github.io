---
layout: publication
title: Topic-based Evaluation For Conversational Bots
authors: Fenfei Guo et al.
conference: Nips.Workshop.ConversationalAI 2017-12-08
year: 2018
citations: 45
bibkey: guo2018topic
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1801.03622'}]
tags: [RAG, Model Architecture, Attention Mechanism, Evaluation]
---
Dialog evaluation is a challenging problem, especially for non task-oriented
dialogs where conversational success is not well-defined. We propose to
evaluate dialog quality using topic-based metrics that describe the ability of
a conversational bot to sustain coherent and engaging conversations on a topic,
and the diversity of topics that a bot can handle. To detect conversation
topics per utterance, we adopt Deep Average Networks (DAN) and train a topic
classifier on a variety of question and query data categorized into multiple
topics. We propose a novel extension to DAN by adding a topic-word attention
table that allows the system to jointly capture topic keywords in an utterance
and perform topic classification. We compare our proposed topic based metrics
with the ratings provided by users and show that our metrics both correlate
with and complement human judgment. Our analysis is performed on tens of
thousands of real human-bot dialogs from the Alexa Prize competition and
highlights user expectations for conversational bots.