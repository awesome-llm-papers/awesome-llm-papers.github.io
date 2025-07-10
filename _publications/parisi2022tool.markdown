---
layout: publication
title: 'TALM: Tool Augmented Language Models'
authors: Aaron Parisi, Yao Zhao, Noah Fiedel
conference: Arxiv
year: 2022
citations: 25
bibkey: parisi2022tool
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.12255'}]
tags: [Transformer, Tools, Training Techniques, Model Architecture]
---
Transformer based language models (LMs) demonstrate increasing performance
with scale across a wide variety of tasks. Scale alone however cannot enable
models to solve tasks that require access to ephemeral, changing, or private
data that was unavailable at training time. Many useful tasks may also benefit
from LMs being able to access APIs that read or modify state. In this work, we
present Tool Augmented Language Models (TALM), combining a text-only approach
to augment language models with non-differentiable tools, and an iterative
"self-play" technique to bootstrap performance starting from few tool
demonstrations. TALM exhibits strong performance on both a knowledge-heavy QA
task and a reasoning oriented math task with simple tools. At a given model
scale, TALM significantly outperforms non-augmented LMs. We further demonstrate
that TALM successfully performs out-of-distribution inferences on both QA and
math tasks, where non-augmented LMs fail. Our results suggest that Tool
Augmented Language Models are a promising direction to enrich LMs'
capabilities, with less dependence on scale.