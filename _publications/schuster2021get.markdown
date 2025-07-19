---
layout: publication
title: Get Your Vitamin C! Robust Fact Verification With Contrastive Evidence
authors: Schuster Tal, Fisch Adam, Barzilay Regina
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: schuster2021get
citations: 104
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.08541'}]
tags: [Security, Training Techniques, Evaluation, ACL, RAG, NAACL, Datasets, Reinforcement
    Learning]
---
Typical fact verification models use retrieved written evidence to verify
claims. Evidence sources, however, often change over time as more information
is gathered and revised. In order to adapt, models must be sensitive to subtle
differences in supporting evidence. We present VitaminC, a benchmark infused
with challenging cases that require fact verification models to discern and
adjust to slight factual changes. We collect over 100,000 Wikipedia revisions
that modify an underlying fact, and leverage these revisions, together with
additional synthetically constructed ones, to create a total of over 400,000
claim-evidence pairs. Unlike previous resources, the examples in VitaminC are
contrastive, i.e., they contain evidence pairs that are nearly identical in
language and content, with the exception that one supports a given claim while
the other does not. We show that training using this design increases
robustness -- improving accuracy by 10% on adversarial fact verification and 6%
on adversarial natural language inference (NLI). Moreover, the structure of
VitaminC leads us to define additional tasks for fact-checking resources:
tagging relevant words in the evidence for verifying the claim, identifying
factual revisions, and providing automatic edits via factually consistent text
generation.