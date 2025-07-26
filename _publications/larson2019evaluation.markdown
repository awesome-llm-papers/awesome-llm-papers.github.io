---
layout: publication
title: An Evaluation Dataset For Intent Classification And Out-of-scope Prediction
authors: Stefan Larson, Anish Mahendran, Joseph J. Peper, Christopher Clarke, Andrew
  Lee, Parker Hill, Jonathan K. Kummerfeld, Kevin Leach, Michael A. Laurenzano, Lingjia
  Tang, Jason Mars
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: larson2019evaluation
citations: 333
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.02027'}]
tags: ["Datasets", "EMNLP", "Evaluation"]
short_authors: Larson et al.
---
Task-oriented dialog systems need to know when a query falls outside their
range of supported intents, but current text classification corpora only define
label sets that cover every example. We introduce a new dataset that includes
queries that are out-of-scope---i.e., queries that do not fall into any of the
system's supported intents. This poses a new challenge because models cannot
assume that every query at inference time belongs to a system-supported intent
class. Our dataset also covers 150 intent classes over 10 domains, capturing
the breadth that a production task-oriented agent must handle. We evaluate a
range of benchmark classifiers on our dataset along with several different
out-of-scope identification schemes. We find that while the classifiers perform
well on in-scope intent classification, they struggle to identify out-of-scope
queries. Our dataset and evaluation fill an important gap in the field,
offering a way of more rigorously and realistically benchmarking text
classification in task-driven dialog systems.