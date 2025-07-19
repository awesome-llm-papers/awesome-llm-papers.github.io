---
layout: publication
title: 'Stress Testing Generalization: How Minor Modifications Undermine Large Language
  Model Performance'
authors: Zhao et al.
conference: IEEE Transactions on Neural Networks
year: 2025
bibkey: zhao2025stress
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.12459'}]
tags: [RAG, GPT, Alt, Evaluation, Ethics And Bias, Model Architecture, Datasets]
---
This paper investigates the fragility of Large Language Models (LLMs) in
generalizing to novel inputs, specifically focusing on minor perturbations in
well-established benchmarks (e.g., slight changes in question format or
distractor length). Despite high benchmark scores, LLMs exhibit significant
accuracy drops and unexpected biases (e.g., preference for longer distractors)
when faced with these minor but content-preserving modifications. For example,
Qwen 2.5 1.5B's MMLU score rises from 60 to 89 and drops from 89 to 36 when
option lengths are changed without altering the question. Even GPT-4
experiences a 25-point accuracy loss when question types are changed, with a
6-point drop across all three modification categories. These analyses suggest
that LLMs rely heavily on superficial cues rather than forming robust, abstract
representations that generalize across formats, lexical variations, and
irrelevant content shifts. This work aligns with the ACL 2025 theme track on
the Generalization of NLP models, proposing a "Generalization Stress Test" to
assess performance shifts under controlled perturbations. The study calls for
reevaluating benchmarks and developing more reliable evaluation methodologies
to capture LLM generalization abilities better.