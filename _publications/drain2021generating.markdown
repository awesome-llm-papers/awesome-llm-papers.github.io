---
layout: publication
title: Generating Code With The Help Of Retrieved Template Functions And Stack Overflow
  Answers
authors: Drain et al.
conference: ACM Transactions on Software Engineering and Methodology
year: 2021
bibkey: drain2021generating
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.05310'}]
tags: [Merging, Tools, Evaluation, LLM For Code, LLM for Code, RAG, Datasets]
---
We approach the important challenge of code autocompletion as an open-domain
task, in which a sequence-to-sequence code generator model is enhanced with the
ability to attend to reference code snippets supplied by a semantic code search
engine. In this work, we present a novel framework to precisely retrieve
template functions as well as intent-snippet pairs and effectively train such a
retrieval-guided code generator. To demonstrate the effectiveness of our model
designs, we perform extensive experiments with CodeSearchNet which contains
template functions and CoNaLa which contains Stack Overflow intent-snippet
pairs. We also investigate different retrieval models, including Elasticsearch,
DPR, and our fusion representation search model, which currently holds the
number one spot on the CodeSearchNet leaderboard. We observe improvements by
leveraging multiple database elements and further gain from retrieving diverse
data points by using Maximal Marginal Relevance. Overall, we see a 4%
improvement to cross-entropy loss, a 15% improvement to edit distance, and a
44% improvement to BLEU score when retrieving template functions. We see
subtler improvements of 2%, 11%, and 6% respectively when retrieving Stack
Overflow intent-snippet pairs. We also create a novel Stack Overflow-Function
Alignment dataset, which consists of 150K tuples of functions and Stack
Overflow intent-snippet pairs that are of help in writing the associated
function, of which 1.7K are manually curated.