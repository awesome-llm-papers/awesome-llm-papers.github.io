---
layout: publication
title: 'Unist: A Prompt-empowered Universal Model For Urban Spatio-temporal Prediction'
authors: Yuan Yuan, Jingtao Ding, Jie Feng, Depeng Jin, Yong Li
conference: 'KDD ''24: The 30th ACM SIGKDD Conference on Knowledge Discovery and Data
  Mining'
year: 2024
citations: 21
bibkey: yuan2024prompt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.11838'}, {name: Code,
    url: 'https://github.com/tsinghua-fib-lab/UniST'}]
tags: [Has Code, Few-Shot, Prompting, Pre-Training, Efficiency and Optimization, Training
    Techniques, Time Series]
---
Urban spatio-temporal prediction is crucial for informed decision-making,
such as traffic management, resource optimization, and emergence response.
Despite remarkable breakthroughs in pretrained natural language models that
enable one model to handle diverse tasks, a universal solution for
spatio-temporal prediction remains challenging Existing prediction approaches
are typically tailored for specific spatio-temporal scenarios, requiring
task-specific model designs and extensive domain-specific training data. In
this study, we introduce UniST, a universal model designed for general urban
spatio-temporal prediction across a wide range of scenarios. Inspired by large
language models, UniST achieves success through: (i) utilizing diverse
spatio-temporal data from different scenarios, (ii) effective pre-training to
capture complex spatio-temporal dynamics, (iii) knowledge-guided prompts to
enhance generalization capabilities. These designs together unlock the
potential of building a universal model for various scenarios Extensive
experiments on more than 20 spatio-temporal scenarios demonstrate UniST's
efficacy in advancing state-of-the-art performance, especially in few-shot and
zero-shot prediction. The datasets and code implementation are released on
https://github.com/tsinghua-fib-lab/UniST.