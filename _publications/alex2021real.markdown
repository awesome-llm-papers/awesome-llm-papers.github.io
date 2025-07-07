---
layout: publication
title: 'RAFT: A Real-world Few-shot Text Classification Benchmark'
authors: Neel Alex et al.
conference: Arxiv
year: 2021
citations: 28
bibkey: alex2021real
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.14076'}]
tags: [GPT, RAG, Few-Shot, Reinforcement Learning, Model Architecture]
---
Large pre-trained language models have shown promise for few-shot learning,
completing text-based tasks given only a few task-specific examples. Will
models soon solve classification tasks that have so far been reserved for human
research assistants? Existing benchmarks are not designed to measure progress
in applied settings, and so don't directly answer this question. The RAFT
benchmark (Real-world Annotated Few-shot Tasks) focuses on naturally occurring
tasks and uses an evaluation setup that mirrors deployment. Baseline
evaluations on RAFT reveal areas current techniques struggle with: reasoning
over long texts and tasks with many classes. Human baselines show that some
classification tasks are difficult for non-expert humans, reflecting that
real-world value sometimes depends on domain expertise. Yet even non-expert
human baseline F1 scores exceed GPT-3 by an average of 0.11. The RAFT datasets
and leaderboard will track which model improvements translate into real-world
benefits at https://raft.elicit.org .