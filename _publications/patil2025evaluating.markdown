---
layout: publication
title: Evaluating Reasoning Llms For Suicide Screening With The Columbia-suicide Severity
  Rating Scale
authors: Patil Avinash, Tao Siru, Gedhu Amardeep
conference: Pediatric Emergency Care
year: 2025
bibkey: patil2025evaluating
citations: 149
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.13480'}]
tags: [GPT, Alt, Tools, Ethics And Bias, Model Architecture, Reinforcement Learning,
  Merging]
---
Suicide prevention remains a critical public health challenge. While online platforms such as Reddit's r/SuicideWatch have historically provided spaces for individuals to express suicidal thoughts and seek community support, the advent of large language models (LLMs) introduces a new paradigm-where individuals may begin disclosing ideation to AI systems instead of humans. This study evaluates the capability of LLMs to perform automated suicide risk assessment using the Columbia-Suicide Severity Rating Scale (C-SSRS). We assess the zero-shot performance of six models-including Claude, GPT, Mistral, and LLaMA-in classifying posts across a 7-point severity scale (Levels 0-6). Results indicate that Claude and GPT closely align with human annotations, while Mistral achieves the lowest ordinal prediction error. Most models exhibit ordinal sensitivity, with misclassifications typically occurring between adjacent severity levels. We further analyze confusion patterns, misclassification sources, and ethical considerations, underscoring the importance of human oversight, transparency, and cautious deployment. Full code and supplementary materials are available at https://github.com/av9ash/llm_cssrs_code.