---
layout: publication
title: Analyzing Bagging Methods For Language Models
authors: Islam et al.
conference: The Annals of Statistics
year: 2022
bibkey: islam2022analyzing
citations: 523
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.09099'}]
tags: [RAG, Pruning, Merging, Efficiency And Optimization]
---
Modern language models leverage increasingly large numbers of parameters to
achieve performance on natural language understanding tasks. Ensembling these
models in specific configurations for downstream tasks show even further
performance improvements. In this paper, we perform an analysis of bagging
language models and compare single language models to bagged ensembles that are
roughly equivalent in terms of final model size. We explore an array of model
bagging configurations for natural language understanding tasks with final
ensemble sizes ranging from 300M parameters to 1.5B parameters and determine
that our ensembling methods are at best roughly equivalent to single LM
baselines. We note other positive effects of bagging and pruning in specific
scenarios according to findings in our experiments such as variance reduction
and minor performance improvements.