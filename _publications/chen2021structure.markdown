---
layout: publication
title: Structure-aware Abstractive Conversation Summarization Via Discourse And Action
  Graphs
authors: Chen Jiaao, Yang Diyi
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: chen2021structure
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.08400'}]
tags: [Model Architecture, Evaluation, ACL, NAACL, Attention Mechanism, Alt]
---
Abstractive conversation summarization has received much attention recently.
However, these generated summaries often suffer from insufficient, redundant,
or incorrect content, largely due to the unstructured and complex
characteristics of human-human interactions. To this end, we propose to
explicitly model the rich structures in conversations for more precise and
accurate conversation summarization, by first incorporating discourse relations
between utterances and action triples ("who-doing-what") in utterances through
structured graphs to better encode conversations, and then designing a
multi-granularity decoder to generate summaries by combining all levels of
information. Experiments show that our proposed models outperform
state-of-the-art methods and generalize well in other domains in terms of both
automatic evaluations and human judgments. We have publicly released our code
at https://github.com/GT-SALT/Structure-Aware-BART.