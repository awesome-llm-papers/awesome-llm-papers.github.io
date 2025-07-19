---
layout: publication
title: 'Task Calibration: Calibrating Large Language Models On Inference Tasks'
authors: Li et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2024
bibkey: li2024task
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.18764'}]
tags: [Prompting, ACL, EMNLP, Few Shot, RAG]
---
Large language models (LLMs) have exhibited impressive zero-shot performance
on inference tasks. However, LLMs may suffer from spurious correlations between
input texts and output labels, which limits LLMs' ability to reason based
purely on general language understanding. In other words, LLMs may make
predictions primarily based on premise or hypothesis, rather than both
components. To address this problem that may lead to unexpected performance
degradation, we propose task calibration (TC), a zero-shot and inference-only
calibration method inspired by mutual information which recovers LLM
performance through task reformulation. TC encourages LLMs to reason based on
both premise and hypothesis, while mitigating the models' over-reliance on
individual premise or hypothesis for inference. Experimental results show that
TC achieves a substantial improvement on 13 inference tasks in the zero-shot
setup. We further validate the effectiveness of TC in few-shot setups and
various natural language understanding tasks. Further analysis indicates that
TC is also robust to prompt templates and has the potential to be integrated
with other calibration methods.