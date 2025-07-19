---
layout: publication
title: 'Textflint: Unified Multilingual Robustness Evaluation Toolkit For Natural
  Language Processing'
authors: Gui et al.
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing:
  System Demonstrations'
year: 2021
bibkey: gui2021textflint
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.11441'}]
tags: [Security, Model Architecture, Tools, BERT, Evaluation, ACL, Reinforcement Learning,
  Alt]
---
Various robustness evaluation methodologies from different perspectives have
been proposed for different natural language processing (NLP) tasks. These
methods have often focused on either universal or task-specific generalization
capabilities. In this work, we propose a multilingual robustness evaluation
platform for NLP tasks (TextFlint) that incorporates universal text
transformation, task-specific transformation, adversarial attack,
subpopulation, and their combinations to provide comprehensive robustness
analysis. TextFlint enables practitioners to automatically evaluate their
models from all aspects or to customize their evaluations as desired with just
a few lines of code. To guarantee user acceptability, all the text
transformations are linguistically based, and we provide a human evaluation for
each one. TextFlint generates complete analytical reports as well as targeted
augmented data to address the shortcomings of the model's robustness. To
validate TextFlint's utility, we performed large-scale empirical evaluations
(over 67,000 evaluations) on state-of-the-art deep learning models, classic
supervised methods, and real-world systems. Almost all models showed
significant performance degradation, including a decline of more than 50% of
BERT's prediction accuracy on tasks such as aspect-level sentiment
classification, named entity recognition, and natural language inference.
Therefore, we call for the robustness to be included in the model evaluation,
so as to promote the healthy development of NLP technology.