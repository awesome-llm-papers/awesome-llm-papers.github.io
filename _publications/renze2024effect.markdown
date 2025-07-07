---
layout: publication
title: The Effect Of Sampling Temperature On Problem Solving In Large Language Models
authors: Matthew Renze, Erhan Guven
conference: Findings of the Association for Computational Linguistics EMNLP 2024 pp.
  7346-7356
year: 2024
citations: 22
bibkey: renze2024effect
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.05201'}, {name: Code,
    url: 'https://github.com/matthewrenze/jhu-llm-temperature'}]
tags: [Has Code, Prompting]
---
In this research study, we empirically investigate the effect of sampling
temperature on the performance of Large Language Models (LLMs) on various
problem-solving tasks. We created a multiple-choice question-and-answer (MCQA)
exam by randomly sampling problems from standard LLM benchmarks. Then, we used
nine popular LLMs with five prompt-engineering techniques to solve the MCQA
problems while increasing the sampling temperature from 0.0 to 1.6. Despite
anecdotal reports to the contrary, our empirical results indicate that changes
in temperature from 0.0 to 1.0 do not have a statistically significant impact
on LLM performance for problem-solving tasks. In addition, these results appear
to generalize across LLMs, prompt-engineering techniques, and problem domains.
All code, data, and supplemental materials are available on GitHub at:
https://github.com/matthewrenze/jhu-llm-temperature