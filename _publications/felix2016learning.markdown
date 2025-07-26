---
layout: publication
title: Learning Distributed Representations Of Sentences From Unlabelled Data
authors: [felix Hill, kyunghyun Cho, anna Korhonen]
conference: 'Proceedings of the 2016 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2016
bibkey: felix2016learning
citations: 529
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/1602.03483v1'}]
tags: ["Training Techniques"]
short_authors: felix Hill, kyunghyun Cho, anna Korhonen
---
Unsupervised methods for learning distributed representations of words are
ubiquitous in today's NLP research, but far less is known about the best ways
to learn distributed phrase or sentence representations from unlabelled data.
This paper is a systematic comparison of models that learn such
representations. We find that the optimal approach depends critically on the
intended application. Deeper, more complex models are preferable for
representations to be used in supervised systems, but shallow log-linear models
work best for building representation spaces that can be decoded with simple
spatial distance metrics. We also propose two new unsupervised
representation-learning objectives designed to optimise the trade-off between
training time, domain portability and performance.