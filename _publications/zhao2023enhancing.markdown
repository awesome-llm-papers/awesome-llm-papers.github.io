---
layout: publication
title: Enhancing Zero-shot Chain-of-thought Reasoning In Large Language Models Through
  Logic
authors: Zhao et al.
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2023
bibkey: zhao2023enhancing
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.13339'}]
tags: [Prompting, Tools, Evaluation, ACL, RAG, Reinforcement Learning, Alt]
---
Recent advancements in large language models have showcased their remarkable
generalizability across various domains. However, their reasoning abilities
still have significant room for improvement, especially when confronted with
scenarios requiring multi-step reasoning. Although large language models
possess extensive knowledge, their reasoning often fails to effectively utilize
this knowledge to establish a coherent thinking paradigm. These models
sometimes show hallucinations as their reasoning procedures are unconstrained
by logical principles. Aiming at improving the zero-shot chain-of-thought
reasoning ability of large language models, we propose LoT (Logical Thoughts),
a self-improvement prompting framework that leverages principles rooted in
symbolic logic, particularly Reductio ad Absurdum, to systematically verify and
rectify the reasoning processes step by step. Experimental evaluations
conducted on language tasks in diverse domains, including arithmetic,
commonsense, symbolic, causal inference, and social problems, demonstrate the
efficacy of enhanced reasoning by logic. The implementation code for LoT can be
accessed at: https://github.com/xf-zhao/LoT.