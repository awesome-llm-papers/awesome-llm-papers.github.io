---
layout: publication
title: Making Neural QA As Simple As Possible But Not Simpler
authors: Dirk Weissenborn, Georg Wiese, Laura Seiffe
conference: Proceedings of the 21st Conference on Computational Natural Language Learning
  (CoNLL 2017)
year: 2017
bibkey: weissenborn2017making
citations: 185
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1703.04816'}]
tags: ["Datasets"]
short_authors: Dirk Weissenborn, Georg Wiese, Laura Seiffe
---
Recent development of large-scale question answering (QA) datasets triggered
a substantial amount of research into end-to-end neural architectures for QA.
Increasingly complex systems have been conceived without comparison to simpler
neural baseline systems that would justify their complexity. In this work, we
propose a simple heuristic that guides the development of neural baseline
systems for the extractive QA task. We find that there are two ingredients
necessary for building a high-performing neural QA system: first, the awareness
of question words while processing the context and second, a composition
function that goes beyond simple bag-of-words modeling, such as recurrent
neural networks. Our results show that FastQA, a system that meets these two
requirements, can achieve very competitive performance compared with existing
models. We argue that this surprising finding puts results of previous systems
and the complexity of recent QA datasets into perspective.