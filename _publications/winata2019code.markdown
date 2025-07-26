---
layout: publication
title: Code-switched Language Models Using Neural Based Synthetic Data From Parallel
  Sentences
authors: Genta Indra Winata, Andrea Madotto, Chien-sheng Wu, Pascale Fung
conference: Proceedings of the 23rd Conference on Computational Natural Language Learning
  (CoNLL)
year: 2019
bibkey: winata2019code
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.08582'}]
tags: ["Training Techniques"]
short_authors: Winata et al.
---
Training code-switched language models is difficult due to lack of data and
complexity in the grammatical structure. Linguistic constraint theories have
been used for decades to generate artificial code-switching sentences to cope
with this issue. However, this require external word alignments or constituency
parsers that create erroneous results on distant languages. We propose a
sequence-to-sequence model using a copy mechanism to generate code-switching
data by leveraging parallel monolingual translations from a limited source of
code-switching data. The model learns how to combine words from parallel
sentences and identifies when to switch one language to the other. Moreover, it
captures code-switching constraints by attending and aligning the words in
inputs, without requiring any external knowledge. Based on experimental
results, the language model trained with the generated sentences achieves
state-of-the-art performance and improves end-to-end automatic speech
recognition.