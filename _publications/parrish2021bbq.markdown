---
layout: publication
title: 'BBQ: A Hand-built Bias Benchmark For Question Answering'
authors: Parrish et al.
conference: 'Findings of the Association for Computational Linguistics: ACL 2022'
year: 2021
bibkey: parrish2021bbq
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.08193'}]
tags: [Ethics And Bias, Evaluation, ACL, RAG, Datasets]
---
It is well documented that NLP models learn social biases, but little work
has been done on how these biases manifest in model outputs for applied tasks
like question answering (QA). We introduce the Bias Benchmark for QA (BBQ), a
dataset of question sets constructed by the authors that highlight attested
social biases against people belonging to protected classes along nine social
dimensions relevant for U.S. English-speaking contexts. Our task evaluates
model responses at two levels: (i) given an under-informative context, we test
how strongly responses reflect social biases, and (ii) given an adequately
informative context, we test whether the model's biases override a correct
answer choice. We find that models often rely on stereotypes when the context
is under-informative, meaning the model's outputs consistently reproduce
harmful biases in this setting. Though models are more accurate when the
context provides an informative answer, they still rely on stereotypes and
average up to 3.4 percentage points higher accuracy when the correct answer
aligns with a social bias than when it conflicts, with this difference widening
to over 5 points on examples targeting gender for most models tested.