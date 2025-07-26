---
layout: publication
title: 'Beat The AI: Investigating Adversarial Human Annotation For Reading Comprehension'
authors: Max Bartolo, Alastair Roberts, Johannes Welbl, Sebastian Riedel, Pontus Stenetorp
conference: Transactions of the Association for Computational Linguistics
year: 2020
bibkey: bartolo2020beat
citations: 120
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2002.00293'}]
tags: ["TACL"]
short_authors: Bartolo et al.
---
Innovations in annotation methodology have been a catalyst for Reading
Comprehension (RC) datasets and models. One recent trend to challenge current
RC models is to involve a model in the annotation process: humans create
questions adversarially, such that the model fails to answer them correctly. In
this work we investigate this annotation methodology and apply it in three
different settings, collecting a total of 36,000 samples with progressively
stronger models in the annotation loop. This allows us to explore questions
such as the reproducibility of the adversarial effect, transfer from data
collected with varying model-in-the-loop strengths, and generalisation to data
collected without a model. We find that training on adversarially collected
samples leads to strong generalisation to non-adversarially collected datasets,
yet with progressive performance deterioration with increasingly stronger
models-in-the-loop. Furthermore, we find that stronger models can still learn
from datasets collected with substantially weaker models-in-the-loop. When
trained on data collected with a BiDAF model in the loop, RoBERTa achieves
39.9F1 on questions that it cannot answer when trained on SQuAD - only
marginally lower than when trained on data collected using RoBERTa itself
(41.0F1).