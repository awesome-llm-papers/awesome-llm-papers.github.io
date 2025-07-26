---
layout: publication
title: 'Nlprolog: Reasoning With Weak Unification For Question Answering In Natural
  Language'
authors: "Leon Weber, Pasquale Minervini, Jannes M\xFCnchmeyer, Ulf Leser, Tim Rockt\xE4\
  schel"
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: weber2019nlprolog
citations: 76
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.06187'}]
tags: ["Training Techniques"]
short_authors: Weber et al.
---
Rule-based models are attractive for various tasks because they inherently
lead to interpretable and explainable decisions and can easily incorporate
prior knowledge. However, such systems are difficult to apply to problems
involving natural language, due to its linguistic variability. In contrast,
neural models can cope very well with ambiguity by learning distributed
representations of words and their composition from data, but lead to models
that are difficult to interpret. In this paper, we describe a model combining
neural networks with logic programming in a novel manner for solving multi-hop
reasoning tasks over natural language. Specifically, we propose to use a Prolog
prover which we extend to utilize a similarity function over pretrained
sentence encoders. We fine-tune the representations for the similarity function
via backpropagation. This leads to a system that can apply rule-based reasoning
to natural language, and induce domain-specific rules from training data. We
evaluate the proposed system on two different question answering tasks, showing
that it outperforms two baselines -- BIDAF (Seo et al., 2016a) and FAST QA
(Weissenborn et al., 2017b) on a subset of the WikiHop corpus and achieves
competitive results on the MedHop data set (Welbl et al., 2017).