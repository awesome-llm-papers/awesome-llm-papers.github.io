---
layout: publication
title: 'Super-naturalinstructions: Generalization Via Declarative Instructions On
  1600+ NLP Tasks'
authors: Yizhong Wang et al.
conference: Arxiv
year: 2022
citations: 89
bibkey: wang2022super
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2204.07705v3'}]
tags: [Training Techniques, Transformer, Model Architecture, GPT]
---
How well can NLP models generalize to a variety of unseen tasks when provided
with task instructions? To address this question, we first introduce
Super-NaturalInstructions, a benchmark of 1,616 diverse NLP tasks and their
expert-written instructions. Our collection covers 76 distinct task types,
including but not limited to classification, extraction, infilling, sequence
tagging, text rewriting, and text composition. This large and diverse
collection of tasks enables rigorous benchmarking of cross-task generalization
under instructions -- training models to follow instructions on a subset of
tasks and evaluating them on the remaining unseen ones. Furthermore, we build
Tk-Instruct, a transformer model trained to follow a variety of in-context
instructions (plain language task definitions or k-shot examples). Our
experiments show that Tk-Instruct outperforms existing instruction-following
models such as InstructGPT by over 9% on our benchmark despite being an order
of magnitude smaller. We further analyze generalization as a function of
various scaling parameters, such as the number of observed tasks, the number of
instances per task, and model sizes. We hope our dataset and model facilitate
future progress towards more general-purpose NLP models.