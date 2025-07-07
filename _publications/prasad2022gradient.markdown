---
layout: publication
title: 'Grips: Gradient-free, Edit-based Instruction Search For Prompting Large Language
  Models'
authors: Archiki Prasad, Peter Hase, Xiang Zhou, Mohit Bansal
conference: Arxiv
year: 2022
citations: 19
bibkey: prasad2022gradient
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.07281'}, {name: Code,
    url: 'https://github.com/archiki/GrIPS'}]
tags: [GPT, RAG, Tools, Has Code, Prompting, Model Architecture]
---
Providing natural language instructions in prompts is a useful new paradigm
for improving task performance of large language models in a zero-shot setting.
Recent work has aimed to improve such prompts via manual rewriting or
gradient-based tuning. However, manual rewriting is time-consuming and requires
subjective interpretation, while gradient-based tuning can be extremely
computationally demanding for large models and may not be feasible for
API-based models. In this work, we introduce Gradient-free Instructional Prompt
Search (GrIPS), a gradient-free, edit-based search approach for improving task
instructions for large language models. GrIPS takes in instructions designed
for humans and automatically returns an improved, edited prompt, while allowing
for API-based tuning. With InstructGPT models, GrIPS improves the average task
performance by up to 4.30 percentage points on eight classification tasks from
the Natural Instructions dataset (with similar improvements for OPT, BLOOM, and
FLAN-T5). We see improvements for both instruction-only prompts and instruction
+ k-shot examples prompts. Notably, GrIPS outperforms manual rewriting and
purely example-based prompts while controlling for the available compute and
data budget. Further, performance of GrIPS is comparable to select
gradient-based tuning approaches. Qualitatively, we show our edits can simplify
instructions and at times make them incoherent but nonetheless improve
accuracy. Our code is available at: https://github.com/archiki/GrIPS