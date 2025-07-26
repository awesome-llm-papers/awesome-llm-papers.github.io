---
layout: publication
title: 'Stanza: A Python Natural Language Processing Toolkit For Many Human Languages'
authors: Peng Qi, Yuhao Zhang, Yuhui Zhang, Jason Bolton, Christopher D. Manning
conference: 'Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics: System Demonstrations'
year: 2020
bibkey: qi2020stanza
citations: 1275
additional_links: [{name: Code, url: 'https://stanfordnlp.github.io/stanza'}, {name: Paper,
    url: 'https://arxiv.org/abs/2003.07082'}]
tags: ["Has Code"]
short_authors: Qi et al.
---
We introduce Stanza, an open-source Python natural language processing
toolkit supporting 66 human languages. Compared to existing widely used
toolkits, Stanza features a language-agnostic fully neural pipeline for text
analysis, including tokenization, multi-word token expansion, lemmatization,
part-of-speech and morphological feature tagging, dependency parsing, and named
entity recognition. We have trained Stanza on a total of 112 datasets,
including the Universal Dependencies treebanks and other multilingual corpora,
and show that the same neural architecture generalizes well and achieves
competitive performance on all languages tested. Additionally, Stanza includes
a native Python interface to the widely used Java Stanford CoreNLP software,
which further extends its functionality to cover other tasks such as
coreference resolution and relation extraction. Source code, documentation, and
pretrained models for 66 languages are available at
https://stanfordnlp.github.io/stanza.