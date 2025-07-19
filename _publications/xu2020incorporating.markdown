---
layout: publication
title: Incorporating External Knowledge Through Pre-training For Natural Language
  To Code Generation
authors: Xu et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: xu2020incorporating
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.09015'}]
tags: [Tools, Training Techniques, LLM For Code, ACL, Evaluation]
---
Open-domain code generation aims to generate code in a general-purpose
programming language (such as Python) from natural language (NL) intents.
Motivated by the intuition that developers usually retrieve resources on the
web when writing code, we explore the effectiveness of incorporating two
varieties of external knowledge into NL-to-code generation: automatically mined
NL-code pairs from the online programming QA forum StackOverflow and
programming language API documentation. Our evaluations show that combining the
two sources with data augmentation and retrieval-based data re-sampling
improves the current state-of-the-art by up to 2.2% absolute BLEU score on the
code generation testbed CoNaLa. The code and resources are available at
https://github.com/neulab/external-knowledge-codegen.