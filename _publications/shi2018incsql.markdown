---
layout: publication
title: 'Incsql: Training Incremental Text-to-sql Parsers With Non-deterministic Oracles'
authors: Shi et al.
conference: Arxiv
year: 2018
bibkey: shi2018incsql
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.05054'}]
tags: [Training Techniques, Evaluation, Datasets]
---
We present a sequence-to-action parsing approach for the natural language to
SQL task that incrementally fills the slots of a SQL query with feasible
actions from a pre-defined inventory. To account for the fact that typically
there are multiple correct SQL queries with the same or very similar semantics,
we draw inspiration from syntactic parsing techniques and propose to train our
sequence-to-action models with non-deterministic oracles. We evaluate our
models on the WikiSQL dataset and achieve an execution accuracy of 83.7% on the
test set, a 2.1% absolute improvement over the models trained with traditional
static oracles assuming a single correct target SQL query. When further
combined with the execution-guided decoding strategy, our model sets a new
state-of-the-art performance at an execution accuracy of 87.1%.