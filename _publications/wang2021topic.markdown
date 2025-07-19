---
layout: publication
title: A Topic Guided Pointer-generator Model For Generating Natural Language Code
  Summaries
authors: Wang et al.
conference: 2011 27th IEEE International Conference on Software Maintenance (ICSM)
year: 2021
bibkey: wang2021topic
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.01642'}]
tags: [Datasets, LLM For Code]
---
Code summarization is the task of generating natural language description of
source code, which is important for program understanding and maintenance.
Existing approaches treat the task as a machine translation problem (e.g., from
Java to English) and applied Neural Machine Translation models to solve the
problem. These approaches only consider a given code unit (e.g., a method)
without its broader context. The lacking of context may hinder the NMT model
from gathering sufficient information for code summarization. Furthermore,
existing approaches use a fixed vocabulary and do not fully consider the words
in code, while many words in the code summary may come from the code. In this
work, we present a neural network model named ToPNN for code summarization,
which uses the topics in a broader context (e.g., class) to guide the neural
networks that combine the generation of new words and the copy of existing
words in code. Based on the model we present an approach for generating natural
language code summaries at the method level (i.e., method comments). We
evaluate our approach using a dataset with 4,203,565 commented Java methods.
The results show significant improvement over state-of-the-art approaches and
confirm the positive effect of class topics and the copy mechanism.