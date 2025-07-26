---
layout: publication
title: Learning To Compute Word Embeddings On The Fly
authors: "Dzmitry Bahdanau, Tom Bosc, Stanis\u0142aw Jastrz\u0119bski, Edward Grefenstette,\
  \ Pascal Vincent, Yoshua Bengio"
conference: Arxiv
year: 2017
bibkey: bahdanau2017learning
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1706.00286'}]
tags: []
short_authors: Bahdanau et al.
---
Words in natural language follow a Zipfian distribution whereby some words
are frequent but most are rare. Learning representations for words in the "long
tail" of this distribution requires enormous amounts of data. Representations
of rare words trained directly on end tasks are usually poor, requiring us to
pre-train embeddings on external data, or treat all rare words as
out-of-vocabulary words with a unique representation. We provide a method for
predicting embeddings of rare words on the fly from small amounts of auxiliary
data with a network trained end-to-end for the downstream task. We show that
this improves results against baselines where embeddings are trained on the end
task for reading comprehension, recognizing textual entailment and language
modeling.