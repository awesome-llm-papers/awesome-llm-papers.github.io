---
layout: publication
title: 'Wikireading: A Novel Large-scale Language Understanding Task Over Wikipedia'
authors: Daniel Hewlett, Alexandre Lacoste, Llion Jones, Illia Polosukhin, Andrew
  Fandrianto, Jay Han, Matthew Kelcey, David Berthelot
conference: 'Proceedings of the 54th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2016
bibkey: hewlett2016wikireading
citations: 149
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1608.03542'}]
tags: ["Datasets"]
short_authors: Hewlett et al.
---
We present WikiReading, a large-scale natural language understanding task and
publicly-available dataset with 18 million instances. The task is to predict
textual values from the structured knowledge base Wikidata by reading the text
of the corresponding Wikipedia articles. The task contains a rich variety of
challenging classification and extraction sub-tasks, making it well-suited for
end-to-end models such as deep neural networks (DNNs). We compare various
state-of-the-art DNN-based architectures for document classification,
information extraction, and question answering. We find that models supporting
a rich answer space, such as word or character sequences, perform best. Our
best-performing model, a word-level sequence to sequence model with a mechanism
to copy out-of-vocabulary words, obtains an accuracy of 71.8%.