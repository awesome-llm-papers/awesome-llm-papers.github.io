---
layout: publication
title: A Simple And Accurate Syntax-agnostic Neural Model For Dependency-based Semantic
  Role Labeling
authors: Marcheggiani Diego, Frolov Anton, Titov Ivan
conference: Proceedings of the 21st Conference on Computational Natural Language Learning
  (CoNLL 2017)
year: 2017
bibkey: marcheggiani2017simple
citations: 122
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1701.02593'}]
tags: [Model Architecture, Reinforcement Learning, Evaluation, Datasets]
---
We introduce a simple and accurate neural model for dependency-based semantic
role labeling. Our model predicts predicate-argument dependencies relying on
states of a bidirectional LSTM encoder. The semantic role labeler achieves
competitive performance on English, even without any kind of syntactic
information and only using local inference. However, when automatically
predicted part-of-speech tags are provided as input, it substantially
outperforms all previous local models and approaches the best reported results
on the English CoNLL-2009 dataset. We also consider Chinese, Czech and Spanish
where our approach also achieves competitive results. Syntactic parsers are
unreliable on out-of-domain data, so standard (i.e., syntactically-informed)
SRL models are hindered when tested in this setting. Our syntax-agnostic model
appears more robust, resulting in the best reported results on standard
out-of-domain test sets.