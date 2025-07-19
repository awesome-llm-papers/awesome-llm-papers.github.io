---
layout: publication
title: A Neural Knowledge Language Model
authors: Ahn et al.
conference: Arxiv
year: 2016
bibkey: ahn2016neural
citations: 126
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1608.00318'}]
tags: [Alt, Reinforcement Learning]
---
Current language models have a significant limitation in the ability to
encode and decode factual knowledge. This is mainly because they acquire such
knowledge from statistical co-occurrences although most of the knowledge words
are rarely observed. In this paper, we propose a Neural Knowledge Language
Model (NKLM) which combines symbolic knowledge provided by the knowledge graph
with the RNN language model. By predicting whether the word to generate has an
underlying fact or not, the model can generate such knowledge-related words by
copying from the description of the predicted fact. In experiments, we show
that the NKLM significantly improves the performance while generating a much
smaller number of unknown words.