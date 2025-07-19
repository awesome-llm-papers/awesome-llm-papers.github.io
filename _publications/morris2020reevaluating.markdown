---
layout: publication
title: Reevaluating Adversarial Examples In Natural Language
authors: Morris et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: morris2020reevaluating
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.14174'}]
tags: [Security, Tools, Survey Paper, ACL, EMNLP]
---
State-of-the-art attacks on NLP models lack a shared definition of a what
constitutes a successful attack. We distill ideas from past work into a unified
framework: a successful natural language adversarial example is a perturbation
that fools the model and follows some linguistic constraints. We then analyze
the outputs of two state-of-the-art synonym substitution attacks. We find that
their perturbations often do not preserve semantics, and 38% introduce
grammatical errors. Human surveys reveal that to successfully preserve
semantics, we need to significantly increase the minimum cosine similarities
between the embeddings of swapped words and between the sentence encodings of
original and perturbed sentences.With constraints adjusted to better preserve
semantics and grammaticality, the attack success rate drops by over 70
percentage points.