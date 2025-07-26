---
layout: publication
title: 'Giving BERT A Calculator: Finding Operations And Arguments With Reading Comprehension'
authors: Daniel Andor, Luheng He, Kenton Lee, Emily Pitler
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: andor2019giving
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.00109'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Andor et al.
---
Reading comprehension models have been successfully applied to extractive
text answers, but it is unclear how best to generalize these models to
abstractive numerical answers. We enable a BERT-based reading comprehension
model to perform lightweight numerical reasoning. We augment the model with a
predefined set of executable 'programs' which encompass simple arithmetic as
well as extraction. Rather than having to learn to manipulate numbers directly,
the model can pick a program and execute it. On the recent Discrete Reasoning
Over Passages (DROP) dataset, designed to challenge reading comprehension
models, we show a 33% absolute improvement by adding shallow programs. The
model can learn to predict new operations when appropriate in a math word
problem setting (Roy and Roth, 2015) with very few training examples.