---
layout: publication
title: 'Zerogen: Efficient Zero-shot Learning Via Dataset Generation'
authors: Jiacheng Ye et al.
conference: Arxiv
year: 2022
citations: 26
bibkey: ye2022efficient
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.07922'}]
tags: [Distillation, GPT, Efficiency and Optimization, Language Modeling, Model Architecture]
---
There is a growing interest in dataset generation recently due to the
superior generative capacity of large pre-trained language models (PLMs). In
this paper, we study a flexible and efficient zero-short learning method,
\textsc\{ZeroGen\}. Given a zero-shot task, we first generate a dataset from
scratch using PLMs in an unsupervised manner. Then, we train a tiny task model
(e.g., LSTM) under the supervision of the synthesized dataset. This approach
allows highly efficient inference as the final task model only has orders of
magnitude fewer parameters comparing to PLMs (e.g., GPT2-XL). Apart from being
annotation-free and efficient, we argue that \textsc\{ZeroGen\} can also provide
useful insights from the perspective of data-free model-agnostic knowledge
distillation, and unreferenced text generation evaluation. Experiments and
analysis on different NLP tasks, namely, text classification, question
answering, and natural language inference, show the effectiveness of
\textsc\{ZeroGen\}.