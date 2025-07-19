---
layout: publication
title: Contextualization Of Morphological Inflection
authors: Vylomova et al.
conference: Yearbook of Morphology
year: 2019
bibkey: vylomova2019contextualization
citations: 347
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.01420'}]
tags: []
---
Critical to natural language generation is the production of correctly
inflected text. In this paper, we isolate the task of predicting a fully
inflected sentence from its partially lemmatized version. Unlike traditional
morphological inflection or surface realization, our task input does not
provide ``gold'' tags that specify what morphological features to realize on
each lemmatized word; rather, such features must be inferred from sentential
context. We develop a neural hybrid graphical model that explicitly
reconstructs morphological features before predicting the inflected forms, and
compare this to a system that directly predicts the inflected forms without
relying on any morphological annotation. We experiment on several typologically
diverse languages from the Universal Dependencies treebanks, showing the
utility of incorporating linguistically-motivated latent variables into NLP
models.