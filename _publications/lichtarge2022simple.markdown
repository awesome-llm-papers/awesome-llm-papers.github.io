---
layout: publication
title: Simple And Effective Gradient-based Tuning Of Sequence-to-sequence Models
authors: Lichtarge Jared, Alberti Chris, Kumar Shankar
conference: Proceedings of the National Academy of Sciences
year: 2022
bibkey: lichtarge2022simple
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2209.04683'}]
tags: [Efficiency And Optimization, Training Techniques, Ethics And Bias]
---
Recent trends towards training ever-larger language models have substantially
improved machine learning performance across linguistic tasks. However, the
huge cost of training larger models can make tuning them prohibitively
expensive, motivating the study of more efficient methods. Gradient-based
hyper-parameter optimization offers the capacity to tune hyper-parameters
during training, yet has not previously been studied in a sequence-to-sequence
setting. We apply a simple and general gradient-based hyperparameter
optimization method to sequence-to-sequence tasks for the first time,
demonstrating both efficiency and performance gains over strong baselines for
both Neural Machine Translation and Natural Language Understanding (NLU) tasks
(via T5 pretraining). For translation, we show the method generalizes across
language pairs, is more efficient than Bayesian hyper-parameter optimization,
and that learned schedules for some hyper-parameters can out-perform even
optimal constant-valued tuning. For T5, we show that learning hyper-parameters
during pretraining can improve performance across downstream NLU tasks. When
learning multiple hyper-parameters concurrently, we show that the global
learning rate can follow a schedule over training that improves performance and
is not explainable by the `short-horizon bias' of greedy methods
\citep\{wu2018\}. We release the code used to facilitate further research.