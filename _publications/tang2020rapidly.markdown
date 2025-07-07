---
layout: publication
title: Rapidly Bootstrapping A Question Answering Dataset For COVID-19
authors: Raphael Tang et al.
conference: Arxiv
year: 2020
citations: 57
bibkey: tang2020rapidly
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.11339'}]
tags: [Tools, Transformer, Model Architecture]
---
We present CovidQA, the beginnings of a question answering dataset
specifically designed for COVID-19, built by hand from knowledge gathered from
Kaggle's COVID-19 Open Research Dataset Challenge. To our knowledge, this is
the first publicly available resource of its type, and intended as a stopgap
measure for guiding research until more substantial evaluation resources become
available. While this dataset, comprising 124 question-article pairs as of the
present version 0.1 release, does not have sufficient examples for supervised
machine learning, we believe that it can be helpful for evaluating the
zero-shot or transfer capabilities of existing models on topics specifically
related to COVID-19. This paper describes our methodology for constructing the
dataset and presents the effectiveness of a number of baselines, including
term-based techniques and various transformer-based models. The dataset is
available at http://covidqa.ai/