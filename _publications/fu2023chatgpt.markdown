---
layout: publication
title: 'Chatgpt For Vulnerability Detection, Classification, And Repair: How Far Are
  We?'
authors: Michael Fu, Chakkrit Tantithamthavorn, Van Nguyen, Trung Le
conference: Arxiv
year: 2023
citations: 36
bibkey: fu2023chatgpt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.09810'}, {name: Code,
    url: 'https://github.com/awsm-research/ChatGPT4Vul'}]
tags: [Training Techniques, GPT, Fine-Tuning, Reinforcement Learning, BERT, Has Code,
  Security, Survey Paper, Prompting, Model Architecture]
---
Large language models (LLMs) like ChatGPT (i.e., gpt-3.5-turbo and gpt-4)
exhibited remarkable advancement in a range of software engineering tasks
associated with source code such as code review and code generation. In this
paper, we undertake a comprehensive study by instructing ChatGPT for four
prevalent vulnerability tasks: function and line-level vulnerability
prediction, vulnerability classification, severity estimation, and
vulnerability repair. We compare ChatGPT with state-of-the-art language models
designed for software vulnerability purposes. Through an empirical assessment
employing extensive real-world datasets featuring over 190,000 C/C++ functions,
we found that ChatGPT achieves limited performance, trailing behind other
language models in vulnerability contexts by a significant margin. The
experimental outcomes highlight the challenging nature of vulnerability
prediction tasks, requiring domain-specific expertise. Despite ChatGPT's
substantial model scale, exceeding that of source code-pre-trained language
models (e.g., CodeBERT) by a factor of 14,000, the process of fine-tuning
remains imperative for ChatGPT to generalize for vulnerability prediction
tasks. We publish the studied dataset, experimental prompts for ChatGPT, and
experimental results at https://github.com/awsm-research/ChatGPT4Vul.