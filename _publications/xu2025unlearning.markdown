---
layout: publication
title: 'Unlearning Isn''t Deletion: Investigating Reversibility Of Machine Unlearning
  In Llms'
authors: Xu et al.
conference: 2021 IEEE Symposium on Security and Privacy (SP)
year: 2025
bibkey: xu2025unlearning
citations: 338
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.16831'}]
tags: [Security, Tools, Fine Tuning, Training Techniques, Evaluation, Privacy]
---
Unlearning in large language models (LLMs) is intended to remove the influence of specific data, yet current evaluations rely heavily on token-level metrics such as accuracy and perplexity. We show that these metrics can be misleading: models often appear to forget, but their original behavior can be rapidly restored with minimal fine-tuning, revealing that unlearning may obscure information rather than erase it. To diagnose this phenomenon, we introduce a representation-level evaluation framework using PCA-based similarity and shift, centered kernel alignment, and Fisher information. Applying this toolkit across six unlearning methods, three domains (text, code, math), and two open-source LLMs, we uncover a critical distinction between reversible and irreversible forgetting. In reversible cases, models suffer token-level collapse yet retain latent features; in irreversible cases, deeper representational damage occurs. We further provide a theoretical account linking shallow weight perturbations near output layers to misleading unlearning signals, and show that reversibility is modulated by task type and hyperparameters. Our findings reveal a fundamental gap in current evaluation practices and establish a new diagnostic foundation for trustworthy unlearning in LLMs. We provide a unified toolkit for analyzing LLM representation changes under unlearning and relearning: https://github.com/XiaoyuXU1/Representational_Analysis_Tools.git.