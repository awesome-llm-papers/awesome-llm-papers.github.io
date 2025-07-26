---
layout: publication
title: Demystifying Prompts In Language Models Via Perplexity Estimation
authors: Hila Gonen, Srini Iyer, Terra Blevins, Noah A. Smith, Luke Zettlemoyer
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2023
bibkey: gonen2022demystifying
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.04037'}]
tags: ["EMNLP", "Prompting"]
short_authors: Gonen et al.
---
Language models can be prompted to perform a wide variety of zero- and
few-shot learning problems. However, performance varies significantly with the
choice of prompt, and we do not yet understand why this happens or how to pick
the best prompts. In this work, we analyze the factors that contribute to this
variance and establish a new empirical hypothesis: the performance of a prompt
is coupled with the extent to which the model is familiar with the language it
contains. Over a wide range of tasks, we show that the lower the perplexity of
the prompt is, the better the prompt is able to perform the task. As a result,
we devise a method for creating prompts: (1) automatically extend a small seed
set of manually written prompts by paraphrasing using GPT3 and backtranslation
and (2) choose the lowest perplexity prompts to get significant gains in
performance.