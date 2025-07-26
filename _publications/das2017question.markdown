---
layout: publication
title: Question Answering On Knowledge Bases And Text Using Universal Schema And Memory
  Networks
authors: Rajarshi Das, Manzil Zaheer, Siva Reddy, Andrew Mccallum
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 2: Short Papers)'
year: 2017
bibkey: das2017question
citations: 143
additional_links: [{name: Code, url: 'https://rajarshd.github.io/TextKBQA\'}, {name: Paper,
    url: 'https://arxiv.org/abs/1704.08384'}]
tags: ["Datasets", "Evaluation", "Has Code"]
short_authors: Das et al.
---
Existing question answering methods infer answers either from a knowledge
base or from raw text. While knowledge base (KB) methods are good at answering
compositional questions, their performance is often affected by the
incompleteness of the KB. Au contraire, web text contains millions of facts
that are absent in the KB, however in an unstructured form. \{\it Universal
schema\} can support reasoning on the union of both structured KBs and
unstructured text by aligning them in a common embedded space. In this paper we
extend universal schema to natural language question answering, employing
*memory networks* to attend to the large body of facts in the combination
of text and KB. Our models can be trained in an end-to-end fashion on
question-answer pairs. Evaluation results on \spades fill-in-the-blank question
answering dataset show that exploiting universal schema for question answering
is better than using either a KB or text alone. This model also outperforms the
current state-of-the-art by 8.5 \\(F_1\\) points.\footnote\{Code and data available
in https://rajarshd.github.io/TextKBQA\}