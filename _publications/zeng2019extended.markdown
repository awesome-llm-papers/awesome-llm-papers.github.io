---
layout: publication
title: Extended Answer And Uncertainty Aware Neural Question Generation
authors: Zeng et al.
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2019
bibkey: zeng2019extended
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.08112'}]
tags: [RAG, EMNLP, Attention Mechanism, Training Techniques, Model Architecture, Datasets]
---
In this paper, we study automatic question generation, the task of creating
questions from corresponding text passages where some certain spans of the text
can serve as the answers. We propose an Extended Answer-aware Network (EAN)
which is trained with Word-based Coverage Mechanism (WCM) and decodes with
Uncertainty-aware Beam Search (UBS). The EAN represents the target answer by
its surrounding sentence with an encoder, and incorporates the information of
the extended answer into paragraph representation with gated
paragraph-to-answer attention to tackle the problem of the inadequate
representation of the target answer. To reduce undesirable repetition, the WCM
penalizes repeatedly attending to the same words at different time-steps in the
training stage. The UBS aims to seek a better balance between the model
confidence in copying words from an input text paragraph and the confidence in
generating words from a vocabulary. We conduct experiments on the SQuAD
dataset, and the results show our approach achieves significant performance
improvement.