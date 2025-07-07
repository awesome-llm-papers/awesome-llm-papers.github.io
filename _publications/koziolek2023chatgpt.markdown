---
layout: publication
title: Chatgpt For PLC/DCS Control Logic Generation
authors: Heiko Koziolek, Sten Gruener, Virendra Ashiwal
conference: Arxiv
year: 2023
citations: 17
bibkey: koziolek2023chatgpt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.15809'}]
tags: [GPT, Fine-Tuning, Reinforcement Learning, Prompting, Model Architecture]
---
Large language models (LLMs) providing generative AI have become popular to
support software engineers in creating, summarizing, optimizing, and
documenting source code. It is still unknown how LLMs can support control
engineers using typical control programming languages in programming tasks.
Researchers have explored GitHub CoPilot or DeepMind AlphaCode for source code
generation but did not yet tackle control logic programming. The contribution
of this paper is an exploratory study, for which we created 100 LLM prompts in
10 representative categories to analyze control logic generation for of PLCs
and DCS from natural language. We tested the prompts by generating answers with
ChatGPT using the GPT-4 LLM. It generated syntactically correct IEC 61131-3
Structured Text code in many cases and demonstrated useful reasoning skills
that could boost control engineer productivity. Our prompt collection is the
basis for a more formal LLM benchmark to test and compare such models for
control logic generation.