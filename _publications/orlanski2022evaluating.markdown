---
layout: publication
title: Evaluating Prompts Across Multiple Choice Tasks In A Zero-shot Setting
authors: Orlanski Gabriel
conference: Natural Language Processing Journal
year: 2022
bibkey: orlanski2022evaluating
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.15754'}]
tags: [Training Techniques, Prompting, Reinforcement Learning, Datasets]
---
Large language models have shown that impressive zero-shot performance can be
achieved through natural language prompts (Radford et al., 2019; Brown et al.,
2020; Sanh et al., 2021). Creating an effective prompt, however, requires
significant trial and error. That \textit\{prompts\} the question: how do the
qualities of a prompt effects its performance? To this end, we collect and
standardize prompts from a diverse range of tasks for use with tasks they were
not designed for. We then evaluate these prompts across fixed multiple choice
datasets for a quantitative analysis of how certain attributes of a prompt
affect performance. We find that including the choices and using prompts not
used during pre-training provide significant improvements. All experiments and
code can be found https://github.com/gabeorlanski/zero-shot-cross-task.