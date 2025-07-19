---
layout: publication
title: Making Retrieval-augmented Language Models Robust To Irrelevant Context
authors: Yoran et al.
conference: Transactions of the Association for Computational Linguistics
year: 2023
bibkey: yoran2023making
citations: 130
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.01558'}]
tags: [Training Techniques, Evaluation, TACL, ACL, RAG, Datasets, Reinforcement Learning]
---
Retrieval-augmented language models (RALMs) hold promise to produce language
understanding systems that are are factual, efficient, and up-to-date. An
important desideratum of RALMs, is that retrieved information helps model
performance when it is relevant, and does not harm performance when it is not.
This is particularly important in multi-hop reasoning scenarios, where misuse
of irrelevant evidence can lead to cascading errors. However, recent work has
shown that retrieval augmentation can sometimes have a negative effect on
performance. In this work, we present a thorough analysis on five open-domain
question answering benchmarks, characterizing cases when retrieval reduces
accuracy. We then propose two methods to mitigate this issue. First, a simple
baseline that filters out retrieved passages that do not entail question-answer
pairs according to a natural language inference (NLI) model. This is effective
in preventing performance reduction, but at a cost of also discarding relevant
passages. Thus, we propose a method for automatically generating data to
fine-tune the language model to properly leverage retrieved passages, using a
mix of relevant and irrelevant contexts at training time. We empirically show
that even 1,000 examples suffice to train the model to be robust to irrelevant
contexts while maintaining high performance on examples with relevant ones.