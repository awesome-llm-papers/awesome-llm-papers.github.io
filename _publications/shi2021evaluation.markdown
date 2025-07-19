---
layout: publication
title: On The Evaluation Of Neural Code Summarization
authors: Shi et al.
conference: Proceedings of the 44th International Conference on Software Engineering
year: 2021
bibkey: shi2021evaluation
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.07112'}]
tags: [LLM For Code, Evaluation, LLM for Code, Datasets, Reinforcement Learning]
---
Source code summaries are important for program comprehension and
maintenance. However, there are plenty of programs with missing, outdated, or
mismatched summaries. Recently, deep learning techniques have been exploited to
automatically generate summaries for given code snippets. To achieve a profound
understanding of how far we are from solving this problem and provide
suggestions to future research, in this paper, we conduct a systematic and
in-depth analysis of 5 state-of-the-art neural code summarization models on 6
widely used BLEU variants, 4 pre-processing operations and their combinations,
and 3 widely used datasets. The evaluation results show that some important
factors have a great influence on the model evaluation, especially on the
performance of models and the ranking among the models. However, these factors
might be easily overlooked. Specifically, (1) the BLEU metric widely used in
existing work of evaluating code summarization models has many variants.
Ignoring the differences among these variants could greatly affect the validity
of the claimed results. Furthermore, we conduct human evaluations and find that
the metric BLEU-DC is most correlated to human perception; (2) code
pre-processing choices can have a large (from -18% to +25%) impact on the
summarization performance and should not be neglected. We also explore the
aggregation of pre-processing combinations and boost the performance of models;
(3) some important characteristics of datasets (corpus sizes, data splitting
methods, and duplication ratios) have a significant impact on model evaluation.
Based on the experimental results, we give actionable suggestions for
evaluating code summarization and choosing the best method in different
scenarios. We also build a shared code summarization toolbox to facilitate
future research.