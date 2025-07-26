---
layout: publication
title: 'Causal Mediation Analysis For Interpreting Neural NLP: The Case Of Gender
  Bias'
authors: Jesse Vig, Sebastian Gehrmann, Yonatan Belinkov, Sharon Qian, Daniel Nevo,
  Simas Sakenis, Jason Huang, Yaron Singer, Stuart Shieber
conference: Arxiv
year: 2020
bibkey: vig2020causal
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.12265'}]
tags: ["Ethics & Fairness"]
short_authors: Vig et al.
---
Common methods for interpreting neural models in natural language processing
typically examine either their structure or their behavior, but not both. We
propose a methodology grounded in the theory of causal mediation analysis for
interpreting which parts of a model are causally implicated in its behavior. It
enables us to analyze the mechanisms by which information flows from input to
output through various model components, known as mediators. We apply this
methodology to analyze gender bias in pre-trained Transformer language models.
We study the role of individual neurons and attention heads in mediating gender
bias across three datasets designed to gauge a model's sensitivity to gender
bias. Our mediation analysis reveals that gender bias effects are (i) sparse,
concentrated in a small part of the network; (ii) synergistic, amplified or
repressed by different components; and (iii) decomposable into effects flowing
directly from the input and indirectly through the mediators.