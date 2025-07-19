---
layout: publication
title: 'Chartqa: A Benchmark For Question Answering About Charts With Visual And Logical
  Reasoning'
authors: Masry et al.
conference: 'Findings of the Association for Computational Linguistics: ACL 2022'
year: 2022
bibkey: masry2022chartqa
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.10244'}]
tags: [Model Architecture, Evaluation, ACL, Transformer, Datasets]
---
Charts are very popular for analyzing data. When exploring charts, people
often ask a variety of complex reasoning questions that involve several logical
and arithmetic operations. They also commonly refer to visual features of a
chart in their questions. However, most existing datasets do not focus on such
complex reasoning questions as their questions are template-based and answers
come from a fixed-vocabulary. In this work, we present a large-scale benchmark
covering 9.6K human-written questions as well as 23.1K questions generated from
human-written chart summaries. To address the unique challenges in our
benchmark involving visual and logical reasoning over charts, we present two
transformer-based models that combine visual features and the data table of the
chart in a unified way to answer questions. While our models achieve the
state-of-the-art results on the previous datasets as well as on our benchmark,
the evaluation also reveals several challenges in answering complex reasoning
questions.