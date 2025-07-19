---
layout: publication
title: 'Prompting Is All You Need: Automated Android Bug Replay With Large Language
  Models'
authors: Feng Sidong, Chen Chunyang
conference: Proceedings of the IEEE/ACM 46th International Conference on Software
  Engineering
year: 2023
bibkey: feng2023prompting
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.01987'}]
tags: [Model Architecture, Prompting, Training Techniques, Efficiency And Optimization,
  Evaluation, LLM For Code, Few Shot, LLM for Code, RAG, GPT]
---
Bug reports are vital for software maintenance that allow users to inform
developers of the problems encountered while using the software. As such,
researchers have committed considerable resources toward automating bug replay
to expedite the process of software maintenance. Nonetheless, the success of
current automated approaches is largely dictated by the characteristics and
quality of bug reports, as they are constrained by the limitations of
manually-crafted patterns and pre-defined vocabulary lists. Inspired by the
success of Large Language Models (LLMs) in natural language understanding, we
propose AdbGPT, a new lightweight approach to automatically reproduce the bugs
from bug reports through prompt engineering, without any training and
hard-coding effort. AdbGPT leverages few-shot learning and chain-of-thought
reasoning to elicit human knowledge and logical reasoning from LLMs to
accomplish the bug replay in a manner similar to a developer. Our evaluations
demonstrate the effectiveness and efficiency of our AdbGPT to reproduce 81.3%
of bug reports in 253.6 seconds, outperforming the state-of-the-art baselines
and ablation studies. We also conduct a small-scale user study to confirm the
usefulness of AdbGPT in enhancing developers' bug replay capabilities.