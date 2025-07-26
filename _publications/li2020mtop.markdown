---
layout: publication
title: 'MTOP: A Comprehensive Multilingual Task-oriented Semantic Parsing Benchmark'
authors: Haoran Li, Abhinav Arora, Shuohui Chen, Anchit Gupta, Sonal Gupta, Yashar
  Mehdad
conference: 'Proceedings of the 16th Conference of the European Chapter of the Association
  for Computational Linguistics: Main Volume'
year: 2021
bibkey: li2020mtop
citations: 114
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2008.09335'}]
tags: ["Datasets", "EACL", "Evaluation"]
short_authors: Li et al.
---
Scaling semantic parsing models for task-oriented dialog systems to new
languages is often expensive and time-consuming due to the lack of available
datasets. Available datasets suffer from several shortcomings: a) they contain
few languages b) they contain small amounts of labeled examples per language c)
they are based on the simple intent and slot detection paradigm for
non-compositional queries. In this paper, we present a new multilingual
dataset, called MTOP, comprising of 100k annotated utterances in 6 languages
across 11 domains. We use this dataset and other publicly available datasets to
conduct a comprehensive benchmarking study on using various state-of-the-art
multilingual pre-trained models for task-oriented semantic parsing. We achieve
an average improvement of +6.3 points on Slot F1 for the two existing
multilingual datasets, over best results reported in their experiments.
Furthermore, we demonstrate strong zero-shot performance using pre-trained
models combined with automatic translation and alignment, and a proposed
distant supervision method to reduce the noise in slot label projection.