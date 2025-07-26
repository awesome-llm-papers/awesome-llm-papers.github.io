---
layout: publication
title: Making Monolingual Sentence Embeddings Multilingual Using Knowledge Distillation
authors: Nils Reimers, Iryna Gurevych
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: reimers2020making
citations: 619
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.09813'}]
tags: ["EMNLP", "Training Techniques"]
short_authors: Nils Reimers, Iryna Gurevych
---
We present an easy and efficient method to extend existing sentence embedding
models to new languages. This allows to create multilingual versions from
previously monolingual models. The training is based on the idea that a
translated sentence should be mapped to the same location in the vector space
as the original sentence. We use the original (monolingual) model to generate
sentence embeddings for the source language and then train a new system on
translated sentences to mimic the original model. Compared to other methods for
training multilingual sentence embeddings, this approach has several
advantages: It is easy to extend existing models with relatively few samples to
new languages, it is easier to ensure desired properties for the vector space,
and the hardware requirements for training is lower. We demonstrate the
effectiveness of our approach for 50+ languages from various language families.
Code to extend sentence embeddings models to more than 400 languages is
publicly available.