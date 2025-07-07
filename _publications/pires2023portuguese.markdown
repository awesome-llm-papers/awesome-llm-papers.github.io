---
layout: publication
title: 'Sabi\''a: Portuguese Large Language Models'
authors: Ramon Pires, Hugo Abonizio, Thales Sales Almeida, Rodrigo Nogueira
conference: Arxiv
year: 2023
citations: 28
bibkey: pires2023portuguese
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.07880'}]
tags: [GPT, Training Techniques, Few-Shot, Reinforcement Learning, Model Architecture]
---
As the capabilities of language models continue to advance, it is conceivable
that "one-size-fits-all" model will remain as the main paradigm. For instance,
given the vast number of languages worldwide, many of which are low-resource,
the prevalent practice is to pretrain a single model on multiple languages. In
this paper, we add to the growing body of evidence that challenges this
practice, demonstrating that monolingual pretraining on the target language
significantly improves models already extensively trained on diverse corpora.
More specifically, we further pretrain GPT-J and LLaMA models on Portuguese
texts using 3% or less of their original pretraining budget. Few-shot
evaluations on Poeta, a suite of 14 Portuguese datasets, reveal that our models
outperform English-centric and multilingual counterparts by a significant
margin. Our best model, Sabi\'a-65B, performs on par with GPT-3.5-turbo. By
evaluating on datasets originally conceived in the target language as well as
translated ones, we study the contributions of language-specific pretraining in
terms of 1) capturing linguistic nuances and structures inherent to the target
language, and 2) enriching the model's knowledge about a domain or culture. Our
results indicate that the majority of the benefits stem from the
domain-specific knowledge acquired through monolingual pretraining.