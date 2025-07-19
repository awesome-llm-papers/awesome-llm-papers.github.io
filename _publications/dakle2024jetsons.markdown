---
layout: publication
title: 'Jetsons At Finnlp 2024: Towards Understanding The ESG Impact Of A News Article
  Using Transformer-based Models'
authors: Dakle et al.
conference: Knowledge-Based Systems
year: 2024
bibkey: dakle2024jetsons
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.00386'}]
tags: [Training Techniques, Evaluation, BERT, Transformer, Model Architecture, Fine
    Tuning, Datasets]
---
In this paper, we describe the different approaches explored by the Jetsons
team for the Multi-Lingual ESG Impact Duration Inference (ML-ESG-3) shared
task. The shared task focuses on predicting the duration and type of the ESG
impact of a news article. The shared task dataset consists of 2,059 news titles
and articles in English, French, Korean, and Japanese languages. For the impact
duration classification task, we fine-tuned XLM-RoBERTa with a custom
fine-tuning strategy and using self-training and DeBERTa-v3 using only English
translations. These models individually ranked first on the leaderboard for
Korean and Japanese and in an ensemble for the English language, respectively.
For the impact type classification task, our XLM-RoBERTa model fine-tuned using
a custom fine-tuning strategy ranked first for the English language.