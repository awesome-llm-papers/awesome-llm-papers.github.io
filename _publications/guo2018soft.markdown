---
layout: publication
title: Soft Layer-specific Multi-task Summarization With Entailment And Question Generation
authors: Han Guo, Ramakanth Pasunuru, Mohit Bansal
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2018
bibkey: guo2018soft
citations: 143
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.11004'}]
tags: ["Datasets"]
short_authors: Han Guo, Ramakanth Pasunuru, Mohit Bansal
---
An accurate abstractive summary of a document should contain all its salient
information and should be logically entailed by the input document. We improve
these important aspects of abstractive summarization via multi-task learning
with the auxiliary tasks of question generation and entailment generation,
where the former teaches the summarization model how to look for salient
questioning-worthy details, and the latter teaches the model how to rewrite a
summary which is a directed-logical subset of the input document. We also
propose novel multi-task architectures with high-level (semantic)
layer-specific sharing across multiple encoder and decoder layers of the three
tasks, as well as soft-sharing mechanisms (and show performance ablations and
analysis examples of each contribution). Overall, we achieve statistically
significant improvements over the state-of-the-art on both the CNN/DailyMail
and Gigaword datasets, as well as on the DUC-2002 transfer setup. We also
present several quantitative and qualitative analysis studies of our model's
learned saliency and entailment skills.