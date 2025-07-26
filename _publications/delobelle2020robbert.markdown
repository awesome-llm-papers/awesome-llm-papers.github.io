---
layout: publication
title: 'Robbert: A Dutch Roberta-based Language Model'
authors: Pieter Delobelle, Thomas Winters, Bettina Berendt
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: delobelle2020robbert
citations: 178
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2001.06286'}]
tags: ["Applications", "EMNLP", "Model Architecture"]
short_authors: Pieter Delobelle, Thomas Winters, Bettina Berendt
---
Pre-trained language models have been dominating the field of natural
language processing in recent years, and have led to significant performance
gains for various complex natural language tasks. One of the most prominent
pre-trained language models is BERT, which was released as an English as well
as a multilingual version. Although multilingual BERT performs well on many
tasks, recent studies show that BERT models trained on a single language
significantly outperform the multilingual version. Training a Dutch BERT model
thus has a lot of potential for a wide range of Dutch NLP tasks. While previous
approaches have used earlier implementations of BERT to train a Dutch version
of BERT, we used RoBERTa, a robustly optimized BERT approach, to train a Dutch
language model called RobBERT. We measured its performance on various tasks as
well as the importance of the fine-tuning dataset size. We also evaluated the
importance of language-specific tokenizers and the model's fairness. We found
that RobBERT improves state-of-the-art results for various tasks, and
especially significantly outperforms other models when dealing with smaller
datasets. These results indicate that it is a powerful pre-trained model for a
large variety of Dutch language tasks. The pre-trained and fine-tuned models
are publicly available to support further downstream Dutch NLP applications.