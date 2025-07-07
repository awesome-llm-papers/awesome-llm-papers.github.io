---
layout: publication
title: Incorporating External Knowledge Through Pre-training For Natural Language
  To Code Generation
authors: Frank F. Xu, Zhengbao Jiang, Pengcheng Yin, Bogdan Vasilescu, Graham Neubig
conference: Arxiv
year: 2020
citations: 24
bibkey: xu2020incorporating
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.09015'}, {name: Code,
    url: 'https://github.com/neulab/external-knowledge-codegen'}]
tags: [Pre-Training, Tools, Training Techniques, Has Code]
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