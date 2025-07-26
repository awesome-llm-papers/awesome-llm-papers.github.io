---
layout: publication
title: Adaptive Document Retrieval For Deep Question Answering
authors: Bernhard Kratzwald, Stefan Feuerriegel
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: kratzwald2018adaptive
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.06528'}]
tags: ["Datasets", "EMNLP", "Evaluation"]
short_authors: Bernhard Kratzwald, Stefan Feuerriegel
---
State-of-the-art systems in deep question answering proceed as follows: (1)
an initial document retrieval selects relevant documents, which (2) are then
processed by a neural network in order to extract the final answer. Yet the
exact interplay between both components is poorly understood, especially
concerning the number of candidate documents that should be retrieved. We show
that choosing a static number of documents -- as used in prior research --
suffers from a noise-information trade-off and yields suboptimal results. As a
remedy, we propose an adaptive document retrieval model. This learns the
optimal candidate number for document retrieval, conditional on the size of the
corpus and the query. We report extensive experimental results showing that our
adaptive approach outperforms state-of-the-art methods on multiple benchmark
datasets, as well as in the context of corpora with variable sizes.