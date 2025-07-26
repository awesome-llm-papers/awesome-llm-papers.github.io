---
layout: publication
title: Neural Module Networks For Reasoning Over Text
authors: Nitish Gupta, Kevin Lin, Dan Roth, Sameer Singh, Matt Gardner
conference: Arxiv
year: 2019
bibkey: gupta2019neural
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1912.04971'}]
tags: ["Datasets", "Ethics & Fairness"]
short_authors: Gupta et al.
---
Answering compositional questions that require multiple steps of reasoning
against text is challenging, especially when they involve discrete, symbolic
operations. Neural module networks (NMNs) learn to parse such questions as
executable programs composed of learnable modules, performing well on synthetic
visual QA domains. However, we find that it is challenging to learn these
models for non-synthetic questions on open-domain text, where a model needs to
deal with the diversity of natural language and perform a broader range of
reasoning. We extend NMNs by: (a) introducing modules that reason over a
paragraph of text, performing symbolic reasoning (such as arithmetic, sorting,
counting) over numbers and dates in a probabilistic and differentiable manner;
and (b) proposing an unsupervised auxiliary loss to help extract arguments
associated with the events in text. Additionally, we show that a limited amount
of heuristically-obtained question program and intermediate module output
supervision provides sufficient inductive bias for accurate learning. Our
proposed model significantly outperforms state-of-the-art models on a subset of
the DROP dataset that poses a variety of reasoning challenges that are covered
by our modules.