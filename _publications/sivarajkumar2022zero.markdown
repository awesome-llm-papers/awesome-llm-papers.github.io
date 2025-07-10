---
layout: publication
title: 'Healthprompt: A Zero-shot Learning Paradigm For Clinical Natural Language
  Processing'
authors: Sonish Sivarajkumar, Yanshan Wang
conference: Arxiv
year: 2022
citations: 24
bibkey: sivarajkumar2022zero
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.05061'}]
tags: [Fine-Tuning, Tools, Prompting, Training Techniques, Merging]
---
Deep learning algorithms are dependent on the availability of large-scale
annotated clinical text datasets. The lack of such publicly available datasets
is the biggest bottleneck for the development of clinical Natural Language
Processing(NLP) systems. Zero-Shot Learning(ZSL) refers to the use of deep
learning models to classify instances from new classes of which no training
data have been seen before. Prompt-based learning is an emerging ZSL technique
where we define task-based templates for NLP tasks. We developed a novel
prompt-based clinical NLP framework called HealthPrompt and applied the
paradigm of prompt-based learning on clinical texts. In this technique, rather
than fine-tuning a Pre-trained Language Model(PLM), the task definitions are
tuned by defining a prompt template. We performed an in-depth analysis of
HealthPrompt on six different PLMs in a no-data setting. Our experiments prove
that prompts effectively capture the context of clinical texts and perform
remarkably well without any training data.