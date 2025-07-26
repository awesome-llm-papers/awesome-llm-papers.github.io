---
layout: publication
title: 'Regression Transformer: Concurrent Sequence Regression And Generation For
  Molecular Language Modeling'
authors: Jannis Born, Matteo Manica
conference: Nature Machine Intelligence
year: 2023
bibkey: born2022regression
citations: 79
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.01338'}]
tags: ["Has Code", "Model Architecture"]
short_authors: Jannis Born, Matteo Manica
---
Despite significant progress of generative models in the natural sciences,
their controllability remains challenging. One fundamentally missing aspect of
molecular or protein generative models is an inductive bias that can reflect
continuous properties of interest. To that end, we propose the Regression
Transformer (RT), a novel method that abstracts regression as a conditional
sequence modeling problem. This introduces a new paradigm of multitask language
models which seamlessly bridge sequence regression and conditional sequence
generation.
  We thoroughly demonstrate that, despite using a nominal-scale training
objective, the RT matches or surpasses the performance of conventional
regression models in property prediction tasks of small molecules, proteins and
chemical reactions. Critically, priming the same model with continuous
properties yields a highly competitive conditional generative model that
outperforms specialized approaches in a substructure-constrained,
property-driven molecule generation benchmark. Our dichotomous approach is
facilitated by a novel, alternating training scheme that enables the model to
decorate seed sequences by desired properties, e.g., to optimize reaction
yield.
  In sum, the RT is the first report of a multitask model that concurrently
excels at predictive and generative tasks in biochemistry. This finds
particular application in property-driven, local exploration of the chemical or
protein space and could pave the road toward foundation models in material
design.
  The code to reproduce all experiments of the paper is available at:
https://github.com/IBM/regression-transformer