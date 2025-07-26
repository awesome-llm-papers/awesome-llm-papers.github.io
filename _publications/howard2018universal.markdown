---
layout: publication
title: Universal Language Model Fine-tuning For Text Classification
authors: Jeremy Howard, Sebastian Ruder
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2018
bibkey: howard2018universal
citations: 3464
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1801.06146'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Jeremy Howard, Sebastian Ruder
---
Inductive transfer learning has greatly impacted computer vision, but
existing approaches in NLP still require task-specific modifications and
training from scratch. We propose Universal Language Model Fine-tuning
(ULMFiT), an effective transfer learning method that can be applied to any task
in NLP, and introduce techniques that are key for fine-tuning a language model.
Our method significantly outperforms the state-of-the-art on six text
classification tasks, reducing the error by 18-24% on the majority of datasets.
Furthermore, with only 100 labeled examples, it matches the performance of
training from scratch on 100x more data. We open-source our pretrained models
and code.