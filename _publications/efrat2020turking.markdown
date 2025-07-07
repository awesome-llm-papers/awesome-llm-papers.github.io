---
layout: publication
title: 'The Turking Test: Can Language Models Understand Instructions?'
authors: Avia Efrat, Omer Levy
conference: Arxiv
year: 2020
citations: 40
bibkey: efrat2020turking
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.11982'}]
tags: [Few-Shot, Reinforcement Learning]
---
Supervised machine learning provides the learner with a set of input-output
examples of the target task. Humans, however, can also learn to perform new
tasks from instructions in natural language. Can machines learn to understand
instructions as well? We present the Turking Test, which examines a model's
ability to follow natural language instructions of varying complexity. These
range from simple tasks, like retrieving the nth word of a sentence, to ones
that require creativity, such as generating examples for SNLI and SQuAD in
place of human intelligence workers ("turkers"). Despite our lenient evaluation
methodology, we observe that a large pretrained language model performs poorly
across all tasks. Analyzing the model's error patterns reveals that the model
tends to ignore explicit instructions and often generates outputs that cannot
be construed as an attempt to solve the task. While it is not yet clear whether
instruction understanding can be captured by traditional language models, the
sheer expressivity of instruction understanding makes it an appealing
alternative to the rising few-shot inference paradigm.