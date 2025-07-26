---
layout: publication
title: 'Neural Semantic Parsing By Character-based Translation: Experiments With Abstract
  Meaning Representations'
authors: Rik van Noord, Johan Bos
conference: Arxiv
year: 2017
bibkey: vannoord2017neural
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1705.09980'}]
tags: ["Training Techniques"]
short_authors: Rik van Noord, Johan Bos
---
We evaluate the character-level translation method for neural semantic
parsing on a large corpus of sentences annotated with Abstract Meaning
Representations (AMRs). Using a sequence-to-sequence model, and some trivial
preprocessing and postprocessing of AMRs, we obtain a baseline accuracy of 53.1
(F-score on AMR-triples). We examine five different approaches to improve this
baseline result: (i) reordering AMR branches to match the word order of the
input sentence increases performance to 58.3; (ii) adding part-of-speech tags
(automatically produced) to the input shows improvement as well (57.2); (iii)
So does the introduction of super characters (conflating frequent sequences of
characters to a single character), reaching 57.4; (iv) optimizing the training
process by using pre-training and averaging a set of models increases
performance to 58.7; (v) adding silver-standard training data obtained by an
off-the-shelf parser yields the biggest improvement, resulting in an F-score of
64.0. Combining all five techniques leads to an F-score of 71.0 on holdout
data, which is state-of-the-art in AMR parsing. This is remarkable because of
the relative simplicity of the approach.