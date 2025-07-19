---
layout: publication
title: 'APPL: A Prompt Programming Language For Harmonious Integration Of Programs
  And Large Language Model Prompts'
authors: Dong et al.
conference: CHI Conference on Human Factors in Computing Systems Extended Abstracts
year: 2024
bibkey: dong2024appl
citations: 103
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.13161'}]
tags: [Prompting, Agentic, Tools, Reinforcement Learning]
---
Large Language Models (LLMs) have become increasingly capable of handling
diverse tasks with the aid of well-crafted prompts and integration of external
tools, but as task complexity rises, the workflow involving LLMs can be
complicated and thus challenging to implement and maintain. To address this
challenge, we propose APPL, A Prompt Programming Language that acts as a bridge
between computer programs and LLMs, allowing seamless embedding of prompts into
Python functions, and vice versa. APPL provides an intuitive and Python-native
syntax, an efficient parallelized runtime with asynchronous semantics, and a
tracing module supporting effective failure diagnosis and replaying without
extra costs. We demonstrate that APPL programs are intuitive, concise, and
efficient through three representative scenarios: Chain-of-Thought with
self-consistency (CoT-SC), ReAct tool use agent, and multi-agent chat.
Experiments on three parallelizable workflows further show that APPL can
effectively parallelize independent LLM calls, with a significant speedup ratio
that almost matches the estimation.