---
layout: publication
title: 'Llama-reviewer: Advancing Code Review Automation With Large Language Models
  Through Parameter-efficient Fine-tuning'
authors: Junyi Lu, Lei Yu, Xiaojia Li, Li Yang, Chun Zuo
conference: 2023 IEEE 34th International Symposium on Software Reliability Engineering
  (ISSRE)
year: 2023
citations: 50
bibkey: lu2023llama
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.11148'}]
tags: [Fine-Tuning, RAG, Survey Paper, Tools, Pre-Training, Training Techniques, Evaluation]
---
The automation of code review activities, a long-standing pursuit in software
engineering, has been primarily addressed by numerous domain-specific
pre-trained models. Despite their success, these models frequently demand
extensive resources for pre-training from scratch. In contrast, Large Language
Models (LLMs) provide an intriguing alternative, given their remarkable
capabilities when supplemented with domain-specific knowledge. However, their
potential for automating code review tasks remains largely unexplored.
  In response to this research gap, we present LLaMA-Reviewer, an innovative
framework that leverages the capabilities of LLaMA, a popular LLM, in the realm
of code review. Mindful of resource constraints, this framework employs
parameter-efficient fine-tuning (PEFT) methods, delivering high performance
while using less than 1% of trainable parameters.
  An extensive evaluation of LLaMA-Reviewer is conducted on two diverse,
publicly available datasets. Notably, even with the smallest LLaMA base model
consisting of 6.7B parameters and a limited number of tuning epochs,
LLaMA-Reviewer equals the performance of existing code-review-focused models.
  The ablation experiments provide insights into the influence of various
fine-tuning process components, including input representation, instruction
tuning, and different PEFT methods. To foster continuous progress in this
field, the code and all PEFT-weight plugins have been made open-source.