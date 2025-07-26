---
layout: publication
title: Exploring Versatile Generative Language Model Via Parameter-efficient Transfer
  Learning
authors: Zhaojiang Lin, Andrea Madotto, Pascale Fung
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: lin2020exploring
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.03829'}]
tags: ["EMNLP", "Fine-Tuning"]
short_authors: Zhaojiang Lin, Andrea Madotto, Pascale Fung
---
Fine-tuning pre-trained generative language models to down-stream language
generation tasks has shown promising results. However, this comes with the cost
of having a single, large model for each task, which is not ideal in
low-memory/power scenarios (e.g., mobile). In this paper, we propose an
effective way to fine-tune multiple down-stream generation tasks simultaneously
using a single, large pre-trained model. The experiments on five diverse
language generation tasks show that by just using an additional 2-3% parameters
for each task, our model can maintain or even improve the performance of
fine-tuning the whole model.