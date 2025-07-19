---
layout: publication
title: Representation Memorization For Fast Learning New Knowledge Without Forgetting
authors: Mi Fei, Lin Tao, Faltings Boi
conference: Lecture Notes in Computer Science
year: 2021
bibkey: mi2021representation
citations: 254
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.12596'}]
tags: [Efficiency And Optimization, Tools, Reinforcement Learning]
---
The ability to quickly learn new knowledge (e.g. new classes or data
distributions) is a big step towards human-level intelligence. In this paper,
we consider scenarios that require learning new classes or data distributions
quickly and incrementally over time, as it often occurs in real-world dynamic
environments. We propose "Memory-based Hebbian Parameter Adaptation" (Hebb) to
tackle the two major challenges (i.e., catastrophic forgetting and sample
efficiency) towards this goal in a unified framework. To mitigate catastrophic
forgetting, Hebb augments a regular neural classifier with a continuously
updated memory module to store representations of previous data. To improve
sample efficiency, we propose a parameter adaptation method based on the
well-known Hebbian theory, which directly "wires" the output network's
parameters with similar representations retrieved from the memory. We
empirically verify the superior performance of Hebb through extensive
experiments on a wide range of learning tasks (image classification, language
model) and learning scenarios (continual, incremental, online). We demonstrate
that Hebb effectively mitigates catastrophic forgetting, and it indeed learns
new knowledge better and faster than the current state-of-the-art.