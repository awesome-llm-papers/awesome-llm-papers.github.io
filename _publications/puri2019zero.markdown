---
layout: publication
title: Zero-shot Text Classification With Generative Language Models
authors: Puri Raul, Catanzaro Bryan
conference: Arxiv
year: 2019
bibkey: puri2019zero
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1912.10165'}]
tags: [Training Techniques, Tools, Evaluation, Language Modeling, Datasets]
---
This work investigates the use of natural language to enable zero-shot model
adaptation to new tasks. We use text and metadata from social commenting
platforms as a source for a simple pretraining task. We then provide the
language model with natural language descriptions of classification tasks as
input and train it to generate the correct answer in natural language via a
language modeling objective. This allows the model to generalize to new
classification tasks without the need for multiple multitask classification
heads. We show the zero-shot performance of these generative language models,
trained with weak supervision, on six benchmark text classification datasets
from the torchtext library. Despite no access to training data, we achieve up
to a 45% absolute improvement in classification accuracy over random or
majority class baselines. These results show that natural language can serve as
simple and powerful descriptors for task adaptation. We believe this points the
way to new metalearning strategies for text problems.