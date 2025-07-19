---
layout: publication
title: Fine-tune BERT For E-commerce Non-default Search Ranking
authors: Jiang et al.
conference: Lecture Notes in Computer Science
year: 2020
bibkey: jiang2020fine
citations: 793
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2008.09689'}]
tags: [RAG, Tools, BERT, Tokenization, Model Architecture]
---
The quality of non-default ranking on e-commerce platforms, such as based on
ascending item price or descending historical sales volume, often suffers from
acute relevance problems, since the irrelevant items are much easier to be
exposed at the top of the ranking results. In this work, we propose a two-stage
ranking scheme, which first recalls wide range of candidate items through
refined query/title keyword matching, and then classifies the recalled items
using BERT-Large fine-tuned on human label data. We also implemented parallel
prediction on multiple GPU hosts and a C++ tokenization custom op of
Tensorflow. In this data challenge, our model won the 1st place in the
supervised phase (based on overall F1 score) and 2nd place in the final phase
(based on average per query F1 score).