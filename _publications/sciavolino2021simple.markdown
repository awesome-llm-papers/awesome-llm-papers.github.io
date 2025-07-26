---
layout: publication
title: Simple Entity-centric Questions Challenge Dense Retrievers
authors: Christopher Sciavolino, Zexuan Zhong, Jinhyuk Lee, Danqi Chen
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: sciavolino2021simple
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.08535'}]
tags: ["EMNLP", "Retrieval Systems"]
short_authors: Sciavolino et al.
---
Open-domain question answering has exploded in popularity recently due to the
success of dense retrieval models, which have surpassed sparse models using
only a few supervised training examples. However, in this paper, we demonstrate
current dense models are not yet the holy grail of retrieval. We first
construct EntityQuestions, a set of simple, entity-rich questions based on
facts from Wikidata (e.g., "Where was Arve Furset born?"), and observe that
dense retrievers drastically underperform sparse methods. We investigate this
issue and uncover that dense retrievers can only generalize to common entities
unless the question pattern is explicitly observed during training. We discuss
two simple solutions towards addressing this critical problem. First, we
demonstrate that data augmentation is unable to fix the generalization problem.
Second, we argue a more robust passage encoder helps facilitate better question
adaptation using specialized question encoders. We hope our work can shed light
on the challenges in creating a robust, universal dense retriever that works
well across different input distributions.