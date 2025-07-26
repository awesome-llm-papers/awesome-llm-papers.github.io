---
layout: publication
title: Learning General Purpose Distributed Sentence Representations Via Large Scale
  Multi-task Learning
authors: Sandeep Subramanian, Adam Trischler, Yoshua Bengio, Christopher J Pal
conference: Arxiv
year: 2018
bibkey: subramanian2018learning
citations: 181
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.00079'}]
tags: ["Fine-Tuning", "Tools", "Training Techniques"]
short_authors: Subramanian et al.
---
A lot of the recent success in natural language processing (NLP) has been
driven by distributed vector representations of words trained on large amounts
of text in an unsupervised manner. These representations are typically used as
general purpose features for words across a range of NLP problems. However,
extending this success to learning representations of sequences of words, such
as sentences, remains an open problem. Recent work has explored unsupervised as
well as supervised learning techniques with different training objectives to
learn general purpose fixed-length sentence representations. In this work, we
present a simple, effective multi-task learning framework for sentence
representations that combines the inductive biases of diverse training
objectives in a single model. We train this model on several data sources with
multiple training objectives on over 100 million sentences. Extensive
experiments demonstrate that sharing a single recurrent sentence encoder across
weakly related tasks leads to consistent improvements over previous methods. We
present substantial improvements in the context of transfer learning and
low-resource settings using our learned general-purpose representations.