---
layout: publication
title: Rapid Word Learning Through Meta In-context Learning
authors: Wang et al.
conference: Machine Learning
year: 2025
bibkey: wang2025rapid
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.14791'}]
tags: [Training Techniques, Tools, Evaluation, In Context Learning, ICML, Few Shot,
  Efficiency And Optimization]
---
Humans can quickly learn a new word from a few illustrative examples, and then systematically and flexibly use it in novel contexts. Yet the abilities of current language models for few-shot word learning, and methods for improving these abilities, are underexplored. In this study, we introduce a novel method, Meta-training for IN-context learNing Of Words (Minnow). This method trains language models to generate new examples of a word's usage given a few in-context examples, using a special placeholder token to represent the new word. This training is repeated on many new words to develop a general word-learning ability. We find that training models from scratch with Minnow on human-scale child-directed language enables strong few-shot word learning, comparable to a large language model (LLM) pre-trained on orders of magnitude more data. Furthermore, through discriminative and generative evaluations, we demonstrate that finetuning pre-trained LLMs with Minnow improves their ability to discriminate between new words, identify syntactic categories of new words, and generate reasonable new usages and definitions for new words, based on one or a few in-context examples. These findings highlight the data efficiency of Minnow and its potential to improve language model performance in word learning tasks.