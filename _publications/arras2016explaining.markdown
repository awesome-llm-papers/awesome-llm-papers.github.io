---
layout: publication
title: Explaining Predictions Of Non-linear Classifiers In NLP
authors: "Leila Arras, Franziska Horn, Gr\xE9goire Montavon, Klaus-robert M\xFCller,\
  \ Wojciech Samek"
conference: Proceedings of the 1st Workshop on Representation Learning for NLP
year: 2016
bibkey: arras2016explaining
citations: 100
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.07298'}]
tags: []
short_authors: Arras et al.
---
Layer-wise relevance propagation (LRP) is a recently proposed technique for
explaining predictions of complex non-linear classifiers in terms of input
variables. In this paper, we apply LRP for the first time to natural language
processing (NLP). More precisely, we use it to explain the predictions of a
convolutional neural network (CNN) trained on a topic categorization task. Our
analysis highlights which words are relevant for a specific prediction of the
CNN. We compare our technique to standard sensitivity analysis, both
qualitatively and quantitatively, using a "word deleting" perturbation
experiment, a PCA analysis, and various visualizations. All experiments
validate the suitability of LRP for explaining the CNN predictions, which is
also in line with results reported in recent image classification studies.