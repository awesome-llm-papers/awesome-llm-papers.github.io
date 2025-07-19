---
layout: publication
title: A Study On How Attention Scores In The BERT Model Are Aware Of Lexical Categories
  In Syntactic And Semantic Tasks On The GLUE Benchmark
authors: Jang Dongjun, Byun Sungjoo, Shin Hyopil
conference: Linguistics and Philosophy
year: 2024
bibkey: jang2024study
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.16447'}]
tags: [Training Techniques, Attention Mechanism, Evaluation, Ethics And Bias, BERT,
  Model Architecture, Fine Tuning, Datasets]
---
This study examines whether the attention scores between tokens in the BERT
model significantly vary based on lexical categories during the fine-tuning
process for downstream tasks. Drawing inspiration from the notion that in human
language processing, syntactic and semantic information is parsed differently,
we categorize tokens in sentences according to their lexical categories and
focus on changes in attention scores among these categories. Our hypothesis
posits that in downstream tasks that prioritize semantic information, attention
scores centered on content words are enhanced, while in cases emphasizing
syntactic information, attention scores centered on function words are
intensified. Through experimentation conducted on six tasks from the GLUE
benchmark dataset, we substantiate our hypothesis regarding the fine-tuning
process. Furthermore, our additional investigations reveal the presence of BERT
layers that consistently assign more bias to specific lexical categories,
irrespective of the task, highlighting the existence of task-agnostic lexical
category preferences.