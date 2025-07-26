---
layout: publication
title: 'Knowledgeable Prompt-tuning: Incorporating Knowledge Into Prompt Verbalizer
  For Text Classification'
authors: Shengding Hu, Ning Ding, Huadong Wang, Zhiyuan Liu, Jingang Wang, Juanzi
  Li, Wei Wu, Maosong Sun
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: hu2021knowledgeable
citations: 194
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.02035'}]
tags: ["Fine-Tuning", "Prompting", "Training Techniques"]
short_authors: Hu et al.
---
Tuning pre-trained language models (PLMs) with task-specific prompts has been
a promising approach for text classification. Particularly, previous studies
suggest that prompt-tuning has remarkable superiority in the low-data scenario
over the generic fine-tuning methods with extra classifiers. The core idea of
prompt-tuning is to insert text pieces, i.e., template, to the input and
transform a classification problem into a masked language modeling problem,
where a crucial step is to construct a projection, i.e., verbalizer, between a
label space and a label word space. A verbalizer is usually handcrafted or
searched by gradient descent, which may lack coverage and bring considerable
bias and high variances to the results. In this work, we focus on incorporating
external knowledge into the verbalizer, forming a knowledgeable prompt-tuning
(KPT), to improve and stabilize prompt-tuning. Specifically, we expand the
label word space of the verbalizer using external knowledge bases (KBs) and
refine the expanded label word space with the PLM itself before predicting with
the expanded label word space. Extensive experiments on zero and few-shot text
classification tasks demonstrate the effectiveness of knowledgeable
prompt-tuning.