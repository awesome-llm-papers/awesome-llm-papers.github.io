---
layout: publication
title: Question Answering By Reasoning Across Documents With Graph Convolutional Networks
authors: Nicola de Cao, Wilker Aziz, Ivan Titov
conference: Proceedings of the 2019 Conference of the North
year: 2019
bibkey: decao2018question
citations: 256
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.09920'}]
tags: ["Datasets"]
short_authors: Nicola de Cao, Wilker Aziz, Ivan Titov
---
Most research in reading comprehension has focused on answering questions
based on individual documents or even single paragraphs. We introduce a neural
model which integrates and reasons relying on information spread within
documents and across multiple documents. We frame it as an inference problem on
a graph. Mentions of entities are nodes of this graph while edges encode
relations between different mentions (e.g., within- and cross-document
co-reference). Graph convolutional networks (GCNs) are applied to these graphs
and trained to perform multi-step reasoning. Our Entity-GCN method is scalable
and compact, and it achieves state-of-the-art results on a multi-document
question answering dataset, WikiHop (Welbl et al., 2018).