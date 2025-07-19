---
layout: publication
title: An Empirical Study On The Usage Of BERT Models For Code Completion
authors: Ciniselli et al.
conference: 2021 IEEE/ACM 18th International Conference on Mining Software Repositories
  (MSR)
year: 2021
bibkey: ciniselli2021empirical
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.07115'}]
tags: [Evaluation, BERT, Model Architecture, Reinforcement Learning, LLM For Code]
---
Code completion is one of the main features of modern Integrated Development
Environments (IDEs). Its objective is to speed up code writing by predicting
the next code token(s) the developer is likely to write. Research in this area
has substantially bolstered the predictive performance of these techniques.
However, the support to developers is still limited to the prediction of the
next few tokens to type. In this work, we take a step further in this direction
by presenting a large-scale empirical study aimed at exploring the capabilities
of state-of-the-art deep learning (DL) models in supporting code completion at
different granularity levels, including single tokens, one or multiple entire
statements, up to entire code blocks (e.g., the iterated block of a for loop).
To this aim, we train and test several adapted variants of the recently
proposed RoBERTa model, and evaluate its predictions from several perspectives,
including: (i) metrics usually adopted when assessing DL generative models
(i.e., BLEU score and Levenshtein distance); (ii) the percentage of perfect
predictions (i.e., the predicted code snippets that match those written by
developers); and (iii) the "semantic" equivalence of the generated code as
compared to the one written by developers. The achieved results show that BERT
models represent a viable solution for code completion, with perfect
predictions ranging from ~7%, obtained when asking the model to guess entire
blocks, up to ~58%, reached in the simpler scenario of few tokens masked from
the same code statement.