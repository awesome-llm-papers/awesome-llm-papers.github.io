---
layout: publication
title: 'Microsoft Translator At WMT 2019: Towards Large-scale Document-level Neural
  Machine Translation'
authors: Marcin Junczys-dowmunt
conference: Arxiv
year: 2019
citations: 30
bibkey: junczysdowmunt2019microsoft
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1907.06170'}]
tags: [Training Techniques, Transformer, Fine-Tuning, BERT, WMT, Model Architecture]
---
This paper describes the Microsoft Translator submissions to the WMT19 news
translation shared task for English-German. Our main focus is document-level
neural machine translation with deep transformer models. We start with strong
sentence-level baselines, trained on large-scale data created via
data-filtering and noisy back-translation and find that back-translation seems
to mainly help with translationese input. We explore fine-tuning techniques,
deeper models and different ensembling strategies to counter these effects.
Using document boundaries present in the authentic and synthetic parallel data,
we create sequences of up to 1000 subword segments and train transformer
translation models. We experiment with data augmentation techniques for the
smaller authentic data with document-boundaries and for larger authentic data
without boundaries. We further explore multi-task training for the
incorporation of document-level source language monolingual data via the
BERT-objective on the encoder and two-pass decoding for combinations of
sentence-level and document-level systems. Based on preliminary human
evaluation results, evaluators strongly prefer the document-level systems over
our comparable sentence-level system. The document-level systems also seem to
score higher than the human references in source-based direct assessment.