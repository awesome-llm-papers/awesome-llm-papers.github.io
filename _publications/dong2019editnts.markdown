---
layout: publication
title: 'Editnts: An Neural Programmer-interpreter Model For Sentence Simplification
  Through Explicit Editing'
authors: Yue Dong, Zichao Li, Mehdi Rezagholizadeh, Jackie Chi Kit Cheung
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: dong2019editnts
citations: 149
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.08104'}]
tags: ["Evaluation"]
short_authors: Dong et al.
---
We present the first sentence simplification model that learns explicit edit
operations (ADD, DELETE, and KEEP) via a neural programmer-interpreter
approach. Most current neural sentence simplification systems are variants of
sequence-to-sequence models adopted from machine translation. These methods
learn to simplify sentences as a byproduct of the fact that they are trained on
complex-simple sentence pairs. By contrast, our neural programmer-interpreter
is directly trained to predict explicit edit operations on targeted parts of
the input sentence, resembling the way that humans might perform simplification
and revision. Our model outperforms previous state-of-the-art neural sentence
simplification models (without external knowledge) by large margins on three
benchmark text simplification corpora in terms of SARI (+0.95 WikiLarge, +1.89
WikiSmall, +1.41 Newsela), and is judged by humans to produce overall better
and simpler output sentences.