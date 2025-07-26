---
layout: publication
title: Targeted Syntactic Evaluation Of Language Models
authors: Rebecca Marvin, Tal Linzen
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: marvin2018targeted
citations: 401
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.09031'}]
tags: ["EMNLP", "Evaluation"]
short_authors: Rebecca Marvin, Tal Linzen
---
We present a dataset for evaluating the grammaticality of the predictions of
a language model. We automatically construct a large number of minimally
different pairs of English sentences, each consisting of a grammatical and an
ungrammatical sentence. The sentence pairs represent different variations of
structure-sensitive phenomena: subject-verb agreement, reflexive anaphora and
negative polarity items. We expect a language model to assign a higher
probability to the grammatical sentence than the ungrammatical one. In an
experiment using this data set, an LSTM language model performed poorly on many
of the constructions. Multi-task training with a syntactic objective (CCG
supertagging) improved the LSTM's accuracy, but a large gap remained between
its performance and the accuracy of human participants recruited online. This
suggests that there is considerable room for improvement over LSTMs in
capturing syntax in a language model.