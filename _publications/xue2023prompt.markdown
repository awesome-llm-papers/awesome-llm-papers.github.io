---
layout: publication
title: Prompt-augmented Temporal Point Process For Streaming Event Sequence
authors: Xue et al.
conference: IEEE Transactions on Neural Networks and Learning Systems
year: 2023
bibkey: xue2023prompt
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.04993'}]
tags: [Prompting, Tools, Reinforcement Learning, Applications, Datasets]
---
Neural Temporal Point Processes (TPPs) are the prevalent paradigm for
modeling continuous-time event sequences, such as user activities on the web
and financial transactions. In real-world applications, event data is typically
received in a *streaming* manner, where the distribution of patterns may
shift over time. Additionally, *privacy and memory constraints* are
commonly observed in practical scenarios, further compounding the challenges.
Therefore, the continuous monitoring of a TPP to learn the streaming event
sequence is an important yet under-explored problem. Our work paper addresses
this challenge by adopting Continual Learning (CL), which makes the model
capable of continuously learning a sequence of tasks without catastrophic
forgetting under realistic constraints. Correspondingly, we propose a simple
yet effective framework, PromptTPP\footnote\{Our code is available at \{\small
\url\{ https://github.com/yanyanSann/PromptTPP\}\}\}, by integrating the base TPP
with a continuous-time retrieval prompt pool. The prompts, small learnable
parameters, are stored in a memory space and jointly optimized with the base
TPP, ensuring that the model learns event streams sequentially without
buffering past examples or task-specific attributes. We present a novel and
realistic experimental setup for modeling event streams, where PromptTPP
consistently achieves state-of-the-art performance across three real user
behavior datasets.