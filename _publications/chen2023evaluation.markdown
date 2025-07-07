---
layout: publication
title: Evaluation Of Chatgpt Family Of Models For Biomedical Reasoning And Classification
authors: Shan Chen et al.
conference: Arxiv
year: 2023
citations: 32
bibkey: chen2023evaluation
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.02496'}]
tags: [Training Techniques, GPT, Fine-Tuning, Tools, BERT, Applications, Prompting,
  Model Architecture]
---
Recent advances in large language models (LLMs) have shown impressive ability
in biomedical question-answering, but have not been adequately investigated for
more specific biomedical applications. This study investigates the performance
of LLMs such as the ChatGPT family of models (GPT-3.5s, GPT-4) in biomedical
tasks beyond question-answering. Because no patient data can be passed to the
OpenAI API public interface, we evaluated model performance with over 10000
samples as proxies for two fundamental tasks in the clinical domain -
classification and reasoning. The first task is classifying whether statements
of clinical and policy recommendations in scientific literature constitute
health advice. The second task is causal relation detection from the biomedical
literature. We compared LLMs with simpler models, such as bag-of-words (BoW)
with logistic regression, and fine-tuned BioBERT models. Despite the excitement
around viral ChatGPT, we found that fine-tuning for two fundamental NLP tasks
remained the best strategy. The simple BoW model performed on par with the most
complex LLM prompting. Prompt engineering required significant investment.