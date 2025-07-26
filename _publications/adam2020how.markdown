---
layout: publication
title: How Much Knowledge Can You Pack Into The Parameters Of A Language Model?
authors: [adam Roberts, colin Raffel, noam Shazeer]
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: adam2020how
citations: 544
additional_links: [{name: Code, url: 'https://goo.gle/t5-cbqa'}, {name: Paper, url: 'http://arxiv.org/abs/2002.08910v4'}]
tags: ["EMNLP", "Fine-Tuning"]
short_authors: adam Roberts, colin Raffel, noam Shazeer
---
It has recently been observed that neural language models trained on
unstructured text can implicitly store and retrieve knowledge using natural
language queries. In this short paper, we measure the practical utility of this
approach by fine-tuning pre-trained models to answer questions without access
to any external context or knowledge. We show that this approach scales with
model size and performs competitively with open-domain systems that explicitly
retrieve answers from an external knowledge source when answering questions. To
facilitate reproducibility and future work, we release our code and trained
models at https://goo.gle/t5-cbqa.