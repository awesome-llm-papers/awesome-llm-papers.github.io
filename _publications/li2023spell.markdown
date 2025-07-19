---
layout: publication
title: 'SPELL: Semantic Prompt Evolution Based On A LLM'
authors: Li Yujian Betterest, Wu Kai
conference: Proceedings of the 32nd ACM International Conference on Information and
  Knowledge Management
year: 2023
bibkey: li2023spell
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.01260'}]
tags: [Prompting, CIKM, Tools]
---
Prompt engineering is a new paradigm for enhancing the performance of trained
neural network models. For optimizing text-style prompts, existing methods
usually individually operate small portions of a text step by step, which
either breaks the fluency or could not globally adjust a prompt. Since large
language models (LLMs) have powerful ability of generating coherent texts token
by token, can we utilize LLMs for improving prompts? Based on this motivation,
in this paper, considering a trained LLM as a text generator, we attempt to
design a black-box evolution algorithm for automatically optimizing texts,
namely SPELL (Semantic Prompt Evolution based on a LLM). The proposed method is
evaluated with different LLMs and evolution parameters in different text tasks.
Experimental results show that SPELL could rapidly improve the prompts indeed.
We further explore the evolution process and discuss on the limitations,
potential possibilities and future work.