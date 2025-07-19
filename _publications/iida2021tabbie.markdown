---
layout: publication
title: 'TABBIE: Pretrained Representations Of Tabular Data'
authors: Iida et al.
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: iida2021tabbie
citations: 97
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.02584'}]
tags: [Model Architecture, Training Techniques, BERT, ACL, NAACL]
---
Existing work on tabular representation learning jointly models tables and
associated text using self-supervised objective functions derived from
pretrained language models such as BERT. While this joint pretraining improves
tasks involving paired tables and text (e.g., answering questions about
tables), we show that it underperforms on tasks that operate over tables
without any associated text (e.g., populating missing cells). We devise a
simple pretraining objective (corrupt cell detection) that learns exclusively
from tabular data and reaches the state-of-the-art on a suite of table based
prediction tasks. Unlike competing approaches, our model (TABBIE) provides
embeddings of all table substructures (cells, rows, and columns), and it also
requires far less compute to train. A qualitative analysis of our model's
learned cell, column, and row representations shows that it understands complex
table semantics and numerical trends.