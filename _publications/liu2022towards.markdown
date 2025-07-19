---
layout: publication
title: Towards Better Few-shot And Finetuning Performance With Forgetful Causal Language
  Models
authors: Liu et al.
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2022
bibkey: liu2022towards
citations: 471
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.13432'}]
tags: [Model Architecture, ACL, Few Shot, RAG, GPT, Attention Mechanism, Alt]
---
Large language models (LLM) trained using the next-token-prediction
objective, such as GPT3 and PaLM, have revolutionized natural language
processing in recent years by showing impressive zero-shot and few-shot
capabilities across a wide range of tasks. In this work, we propose a simple
technique that significantly boosts the performance of LLMs without adding
computational cost. Our key observation is that, by performing the next token
prediction task with randomly selected past tokens masked out, we can improve
the quality of the learned representations for downstream language
understanding tasks. We hypothesize that randomly masking past tokens prevents
over-attending to recent tokens and encourages attention to tokens in the
distant past. We find that our method, Forgetful Causal Masking (FCM),
significantly improves both few-shot and finetuning performance of PaLM. We
further consider a simple extension, T-FCM, which introduces bidirectional
context to causal language model without altering the sequence order, and
further improves finetuning performance.