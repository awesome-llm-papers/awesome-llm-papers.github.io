---
layout: publication
title: Dialogue Generation On Infrequent Sentence Functions Via Structured Meta-learning
authors: Yifan Gao, Piji Li, Wei Bi, Xiaojiang Liu, Michael R. Lyu, Irwin King
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: gao2020dialogue
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.01495'}]
tags: ["Dialogue & Multi Turn", "EMNLP"]
short_authors: Gao et al.
---
Sentence function is an important linguistic feature indicating the
communicative purpose in uttering a sentence. Incorporating sentence functions
into conversations has shown improvements in the quality of generated
responses. However, the number of utterances for different types of
fine-grained sentence functions is extremely imbalanced. Besides a small number
of high-resource sentence functions, a large portion of sentence functions is
infrequent. Consequently, dialogue generation conditioned on these infrequent
sentence functions suffers from data deficiency. In this paper, we investigate
a structured meta-learning (SML) approach for dialogue generation on infrequent
sentence functions. We treat dialogue generation conditioned on different
sentence functions as separate tasks, and apply model-agnostic meta-learning to
high-resource sentence functions data. Furthermore, SML enhances meta-learning
effectiveness by promoting knowledge customization among different sentence
functions but simultaneously preserving knowledge generalization for similar
sentence functions. Experimental results demonstrate that SML not only improves
the informativeness and relevance of generated responses, but also can generate
responses consistent with the target sentence functions.