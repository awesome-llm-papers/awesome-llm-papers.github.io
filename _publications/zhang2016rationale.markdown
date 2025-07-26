---
layout: publication
title: Rationale-augmented Convolutional Neural Networks For Text Classification
authors: Ye Zhang, Iain Marshall, Byron C. Wallace
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: zhang2016rationale
citations: 259
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1605.04469'}]
tags: ["EMNLP"]
short_authors: Ye Zhang, Iain Marshall, Byron C. Wallace
---
We present a new Convolutional Neural Network (CNN) model for text
classification that jointly exploits labels on documents and their component
sentences. Specifically, we consider scenarios in which annotators explicitly
mark sentences (or snippets) that support their overall document
categorization, i.e., they provide rationales. Our model exploits such
supervision via a hierarchical approach in which each document is represented
by a linear combination of the vector representations of its component
sentences. We propose a sentence-level convolutional model that estimates the
probability that a given sentence is a rationale, and we then scale the
contribution of each sentence to the aggregate document representation in
proportion to these estimates. Experiments on five classification datasets that
have document labels and associated rationales demonstrate that our approach
consistently outperforms strong baselines. Moreover, our model naturally
provides explanations for its predictions.