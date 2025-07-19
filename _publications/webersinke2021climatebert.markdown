---
layout: publication
title: 'Climatebert: A Pretrained Language Model For Climate-related Text'
authors: Webersinke et al.
conference: SSRN Electronic Journal
year: 2021
bibkey: webersinke2021climatebert
citations: 103
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.12010'}]
tags: [RAG, Training Techniques, Masked Language Model, Transformer, BERT, Model Architecture]
---
Over the recent years, large pretrained language models (LM) have
revolutionized the field of natural language processing (NLP). However, while
pretraining on general language has been shown to work very well for common
language, it has been observed that niche language poses problems. In
particular, climate-related texts include specific language that common LMs can
not represent accurately. We argue that this shortcoming of today's LMs limits
the applicability of modern NLP to the broad field of text processing of
climate-related texts. As a remedy, we propose CLIMATEBERT, a transformer-based
language model that is further pretrained on over 2 million paragraphs of
climate-related texts, crawled from various sources such as common news,
research articles, and climate reporting of companies. We find that CLIMATEBERT
leads to a 48% improvement on a masked language model objective which, in turn,
leads to lowering error rates by 3.57% to 35.71% for various climate-related
downstream tasks like text classification, sentiment analysis, and
fact-checking.