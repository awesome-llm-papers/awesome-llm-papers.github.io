---
layout: publication
title: Exploring Fluent Query Reformulations With Text-to-text Transformers And Reinforcement
  Learning
authors: Chen Jerry Zikun, Yu Shi, Wang Haoran
conference: 2013 35th International Conference on Software Engineering (ICSE)
year: 2020
bibkey: chen2020exploring
citations: 131
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.10033'}]
tags: [Model Architecture, Tools, Efficiency And Optimization, Evaluation, LLM For
    Code, Agentic, LLM for Code, RAG, Transformer, Reinforcement Learning, Alt]
---
Query reformulation aims to alter noisy or ambiguous text sequences into
coherent ones closer to natural language questions. This is to prevent errors
from propagating in a client-facing pipeline and promote better communication
with users. Besides, it is crucial to maintain performance in downstream
environments like question answering when rephrased queries are given as input.
We show that under the previous framework (AQA), attempts to alter RL
algorithms do not bring significant benefits to either reward acquisition or
sequence fluency. Instead, we leverage a query-reformulating text-to-text
transformer (QRT5) and apply policy-based RL algorithms to further nudge this
reformulator and obtain better answers downstream by generating
reward-acquiring query trajectories. QRT5 shows better sample efficiency in RL
to achieve the same level of QA performance as the previous approach. It can
generate reformulations with more readability based on query well-formedness
evaluations and can generalize to out-of-sample data. Our framework is
demonstrated to be flexible, allowing reward signals to be sourced from
different downstream environments such as intent classification.