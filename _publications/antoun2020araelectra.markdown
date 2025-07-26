---
layout: publication
title: 'Araelectra: Pre-training Text Discriminators For Arabic Language Understanding'
authors: Wissam Antoun, Fady Baly, Hazem Hajj
conference: Arxiv
year: 2020
bibkey: antoun2020araelectra
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.15516'}]
tags: ["Training Techniques"]
short_authors: Wissam Antoun, Fady Baly, Hazem Hajj
---
Advances in English language representation enabled a more sample-efficient
pre-training task by Efficiently Learning an Encoder that Classifies Token
Replacements Accurately (ELECTRA). Which, instead of training a model to
recover masked tokens, it trains a discriminator model to distinguish true
input tokens from corrupted tokens that were replaced by a generator network.
On the other hand, current Arabic language representation approaches rely only
on pretraining via masked language modeling. In this paper, we develop an
Arabic language representation model, which we name AraELECTRA. Our model is
pretrained using the replaced token detection objective on large Arabic text
corpora. We evaluate our model on multiple Arabic NLP tasks, including reading
comprehension, sentiment analysis, and named-entity recognition and we show
that AraELECTRA outperforms current state-of-the-art Arabic language
representation models, given the same pretraining data and with even a smaller
model size.