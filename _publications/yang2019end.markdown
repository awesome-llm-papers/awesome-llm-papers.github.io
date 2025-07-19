---
layout: publication
title: End-to-end Open-domain Question Answering With Bertserini
authors: Yang et al.
conference: Proceedings of the 2019 Conference of the North
year: 2019
bibkey: yang2019end
citations: 160
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.01718'}]
tags: [Training Techniques, Evaluation, BERT, Model Architecture, Fine Tuning, Datasets]
---
We demonstrate an end-to-end question answering system that integrates BERT
with the open-source Anserini information retrieval toolkit. In contrast to
most question answering and reading comprehension models today, which operate
over small amounts of input text, our system integrates best practices from IR
with a BERT-based reader to identify answers from a large corpus of Wikipedia
articles in an end-to-end fashion. We report large improvements over previous
results on a standard benchmark test collection, showing that fine-tuning
pretrained BERT with SQuAD is sufficient to achieve high accuracy in
identifying answer spans.