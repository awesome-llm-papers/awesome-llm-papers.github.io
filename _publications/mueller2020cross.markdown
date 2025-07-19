---
layout: publication
title: Cross-linguistic Syntactic Evaluation Of Word Prediction Models
authors: Mueller et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: mueller2020cross
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00187'}]
tags: [ACL, Model Architecture, BERT, Evaluation]
---
A range of studies have concluded that neural word prediction models can
distinguish grammatical from ungrammatical sentences with high accuracy.
However, these studies are based primarily on monolingual evidence from
English. To investigate how these models' ability to learn syntax varies by
language, we introduce CLAMS (Cross-Linguistic Assessment of Models on Syntax),
a syntactic evaluation suite for monolingual and multilingual models. CLAMS
includes subject-verb agreement challenge sets for English, French, German,
Hebrew and Russian, generated from grammars we develop. We use CLAMS to
evaluate LSTM language models as well as monolingual and multilingual BERT.
Across languages, monolingual LSTMs achieved high accuracy on dependencies
without attractors, and generally poor accuracy on agreement across object
relative clauses. On other constructions, agreement accuracy was generally
higher in languages with richer morphology. Multilingual models generally
underperformed monolingual models. Multilingual BERT showed high syntactic
accuracy on English, but noticeable deficiencies in other languages.