---
layout: publication
title: Review Conversational Reading Comprehension
authors: Hu Xu, Bing Liu, Lei Shu, Philip S. Yu
conference: Arxiv
year: 2019
citations: 18
bibkey: xu2019review
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.00821'}, {name: Code,
    url: 'https://github.com/howardhsu/RCRC'}]
tags: [Training Techniques, RAG, Pre-Training, Fine-Tuning, Agentic, BERT, Has Code,
  Survey Paper, Model Architecture]
---
Inspired by conversational reading comprehension (CRC), this paper studies a
novel task of leveraging reviews as a source to build an agent that can answer
multi-turn questions from potential consumers of online businesses. We first
build a review CRC dataset and then propose a novel task-aware pre-tuning step
running between language model (e.g., BERT) pre-training and domain-specific
fine-tuning. The proposed pre-tuning requires no data annotation, but can
greatly enhance the performance on our end task. Experimental results show that
the proposed approach is highly effective and has competitive performance as
the supervised approach. The dataset is available at
https://github.com/howardhsu/RCRC