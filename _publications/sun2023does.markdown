---
layout: publication
title: Does Fine-tuning GPT-3 With The Openai API Leak Personally-identifiable Information?
authors: Sun et al.
conference: World Patent Information
year: 2023
bibkey: sun2023does
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.16382'}]
tags: [RAG, Training Techniques, GPT, Prompting, Tools, BERT, Model Architecture,
  Reinforcement Learning, Security, Fine Tuning, Datasets]
---
Machine learning practitioners often fine-tune generative pre-trained models
like GPT-3 to improve model performance at specific tasks. Previous works,
however, suggest that fine-tuned machine learning models memorize and emit
sensitive information from the original fine-tuning dataset. Companies such as
OpenAI offer fine-tuning services for their models, but no prior work has
conducted a memorization attack on any closed-source models. In this work, we
simulate a privacy attack on GPT-3 using OpenAI's fine-tuning API. Our
objective is to determine if personally identifiable information (PII) can be
extracted from this model. We (1) explore the use of naive prompting methods on
a GPT-3 fine-tuned classification model, and (2) we design a practical word
generation task called Autocomplete to investigate the extent of PII
memorization in fine-tuned GPT-3 within a real-world context. Our findings
reveal that fine-tuning GPT3 for both tasks led to the model memorizing and
disclosing critical personally identifiable information (PII) obtained from the
underlying fine-tuning dataset. To encourage further research, we have made our
codes and datasets publicly available on GitHub at:
https://github.com/albertsun1/gpt3-pii-attacks