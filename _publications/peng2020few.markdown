---
layout: publication
title: Few-shot Natural Language Generation For Task-oriented Dialog
authors: Baolin Peng et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
citations: 51
bibkey: peng2020few
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2002.12328'}]
tags: [Model Architecture, Few-Shot, Applications, GPT, Evaluation]
---
As a crucial component in task-oriented dialog systems, the Natural Language
Generation (NLG) module converts a dialog act represented in a semantic form
into a response in natural language. The success of traditional template-based
or statistical models typically relies on heavily annotated data, which is
infeasible for new domains. Therefore, it is pivotal for an NLG system to
generalize well with limited labelled data in real applications. To this end,
we present FewShotWoz, the first NLG benchmark to simulate the few-shot
learning setting in task-oriented dialog systems. Further, we develop the
SC-GPT model. It is pre-trained on a large set of annotated NLG corpus to
acquire the controllable generation ability, and fine-tuned with only a few
domain-specific labels to adapt to new domains. Experiments on FewShotWoz and
the large Multi-Domain-WOZ datasets show that the proposed SC-GPT significantly
outperforms existing methods, measured by various automatic metrics and human
evaluations.