---
layout: publication
title: Reducing Sentiment Bias In Language Models Via Counterfactual Evaluation
authors: Po-sen Huang, Huan Zhang, Ray Jiang, Robert Stanforth, Johannes Welbl, Jack
  Rae, Vishal Maini, Dani Yogatama, Pushmeet Kohli
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: huang2019reducing
citations: 113
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.03064'}]
tags: ["EMNLP", "Evaluation"]
short_authors: Huang et al.
---
Advances in language modeling architectures and the availability of large
text corpora have driven progress in automatic text generation. While this
results in models capable of generating coherent texts, it also prompts models
to internalize social biases present in the training corpus. This paper aims to
quantify and reduce a particular type of bias exhibited by language models:
bias in the sentiment of generated text. Given a conditioning context (e.g., a
writing prompt) and a language model, we analyze if (and how) the sentiment of
the generated text is affected by changes in values of sensitive attributes
(e.g., country names, occupations, genders) in the conditioning context using a
form of counterfactual evaluation. We quantify sentiment bias by adopting
individual and group fairness metrics from the fair machine learning
literature, and demonstrate that large-scale models trained on two different
corpora (news articles, and Wikipedia) exhibit considerable levels of bias. We
then propose embedding and sentiment prediction-derived regularization on the
language model's latent representations. The regularizations improve fairness
metrics while retaining comparable levels of perplexity and semantic
similarity.