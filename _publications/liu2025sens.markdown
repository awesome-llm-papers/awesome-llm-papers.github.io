---
layout: publication
title: 'Sens-merging: Sensitivity-guided Parameter Balancing For Merging Large Language
  Models'
authors: Liu et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: liu2025sens
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.12420'}]
tags: [Reinforcement Learning, Training Techniques, Merging, LLM For Code]
---
Recent advances in large language models have led to numerous
task-specialized fine-tuned variants, creating a need for efficient model
merging techniques that preserve specialized capabilities while avoiding costly
retraining. While existing task vector-based merging methods show promise, they
typically apply uniform coefficients across all parameters, overlooking varying
parameter importance both within and across tasks. We present Sens-Merging, a
sensitivity-guided coefficient adjustment method that enhances existing model
merging techniques by operating at both task-specific and cross-task levels.
Our method analyzes parameter sensitivity within individual tasks and evaluates
cross-task transferability to determine optimal merging coefficients. Extensive
experiments on Mistral 7B and LLaMA2-7B/13B models demonstrate that
Sens-Merging significantly improves performance across general knowledge,
mathematical reasoning, and code generation tasks. Notably, when combined with
existing merging techniques, our method enables merged models to outperform
specialized fine-tuned models, particularly in code generation tasks. Our
findings reveal important trade-offs between task-specific and cross-task
scalings, providing insights for future model merging strategies.