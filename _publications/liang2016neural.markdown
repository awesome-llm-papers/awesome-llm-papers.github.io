---
layout: publication
title: 'Neural Symbolic Machines: Learning Semantic Parsers On Freebase With Weak
  Supervision'
authors: Liang et al.
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2016
bibkey: liang2016neural
citations: 382
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.00020'}]
tags: [Pruning, Training Techniques, Efficiency And Optimization, ACL, Datasets, Reinforcement
    Learning]
---
Harnessing the statistical power of neural networks to perform language
understanding and symbolic reasoning is difficult, when it requires executing
efficient discrete operations against a large knowledge-base. In this work, we
introduce a Neural Symbolic Machine, which contains (a) a neural "programmer",
i.e., a sequence-to-sequence model that maps language utterances to programs
and utilizes a key-variable memory to handle compositionality (b) a symbolic
"computer", i.e., a Lisp interpreter that performs program execution, and helps
find good programs by pruning the search space. We apply REINFORCE to directly
optimize the task reward of this structured prediction problem. To train with
weak supervision and improve the stability of REINFORCE, we augment it with an
iterative maximum-likelihood training process. NSM outperforms the
state-of-the-art on the WebQuestionsSP dataset when trained from
question-answer pairs only, without requiring any feature engineering or
domain-specific knowledge.