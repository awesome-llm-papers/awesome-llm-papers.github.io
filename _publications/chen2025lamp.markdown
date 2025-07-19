---
layout: publication
title: 'LAMP: Extracting Locally Linear Decision Surfaces From LLM World Models'
authors: Chen et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: chen2025lamp
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.11772'}]
tags: [Interpretability And Explainability, Prompting, Tools, Reinforcement Learning,
  Responsible AI]
---
We introduce LAMP (Linear Attribution Mapping Probe), a method that shines light onto a black-box language model's decision surface and studies how reliably a model maps its stated reasons to its predictions through a locally linear model approximating the decision surface. LAMP treats the model's own self-reported explanations as a coordinate system and fits a locally linear surrogate that links those weights to the model's output. By doing so, it reveals which stated factors steer the model's decisions, and by how much. We apply LAMP to three tasks: sentiment analysis, controversial-topic detection, and safety-prompt auditing. Across these tasks, LAMP reveals that many LLMs exhibit locally linear decision landscapes. In addition, these surfaces correlate with human judgments on explanation quality and, on a clinical case-file data set, aligns with expert assessments. Since LAMP operates without requiring access to model gradients, logits, or internal activations, it serves as a practical and lightweight framework for auditing proprietary language models, and enabling assessment of whether a model behaves consistently with the explanations it provides.