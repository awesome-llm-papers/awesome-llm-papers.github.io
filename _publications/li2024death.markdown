---
layout: publication
title: The Death Of Feature Engineering? BERT With Linguistic Features On Squad 2.0
authors: Li Jiawei, Zhang Yue
conference: Arxiv
year: 2024
bibkey: li2024death
citations: 120
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.03184'}]
tags: [Model Architecture, Evaluation, BERT]
---
Machine reading comprehension is an essential natural language processing
task, which takes into a pair of context and query and predicts the
corresponding answer to query. In this project, we developed an end-to-end
question answering model incorporating BERT and additional linguistic features.
We conclude that the BERT base model will be improved by incorporating the
features. The EM score and F1 score are improved 2.17 and 2.14 compared with
BERT(base). Our best single model reaches EM score 76.55 and F1 score 79.97 in
the hidden test set. Our error analysis also shows that the linguistic
architecture can help model understand the context better in that it can locate
answers that BERT only model predicted "No Answer" wrongly.