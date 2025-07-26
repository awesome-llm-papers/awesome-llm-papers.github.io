---
layout: publication
title: Contextualized Perturbation For Textual Adversarial Attack
authors: Dianqi Li, Yizhe Zhang, Hao Peng, Liqun Chen, Chris Brockett, Ming-ting Sun,
  Bill Dolan
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: li2020contextualized
citations: 162
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.07502'}]
tags: ["Evaluation", "NAACL", "Security"]
short_authors: Li et al.
---
Adversarial examples expose the vulnerabilities of natural language
processing (NLP) models, and can be used to evaluate and improve their
robustness. Existing techniques of generating such examples are typically
driven by local heuristic rules that are agnostic to the context, often
resulting in unnatural and ungrammatical outputs. This paper presents CLARE, a
ContextuaLized AdversaRial Example generation model that produces fluent and
grammatical outputs through a mask-then-infill procedure. CLARE builds on a
pre-trained masked language model and modifies the inputs in a context-aware
manner. We propose three contextualized perturbations, Replace, Insert and
Merge, allowing for generating outputs of varied lengths. With a richer range
of available strategies, CLARE is able to attack a victim model more
efficiently with fewer edits. Extensive experiments and human evaluation
demonstrate that CLARE outperforms the baselines in terms of attack success
rate, textual similarity, fluency and grammaticality.