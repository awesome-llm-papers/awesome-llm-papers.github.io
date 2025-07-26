---
layout: publication
title: Dynamic Entity Representations In Neural Language Models
authors: Yangfeng Ji, Chenhao Tan, Sebastian Martschat, Yejin Choi, Noah A. Smith
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: ji2017dynamic
citations: 108
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1708.00781'}]
tags: ["EMNLP", "Memory & Context", "Model Architecture"]
short_authors: Ji et al.
---
Understanding a long document requires tracking how entities are introduced
and evolve over time. We present a new type of language model, EntityNLM, that
can explicitly model entities, dynamically update their representations, and
contextually generate their mentions. Our model is generative and flexible; it
can model an arbitrary number of entities in context while generating each
entity mention at an arbitrary length. In addition, it can be used for several
different tasks such as language modeling, coreference resolution, and entity
prediction. Experimental results with all these tasks demonstrate that our
model consistently outperforms strong baselines and prior work.