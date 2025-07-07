---
layout: publication
title: 'Code Llama: Open Foundation Models For Code'
authors: "Baptiste Rozi\xE8re et al."
conference: Arxiv
year: 2023
citations: 212
bibkey: "rozi\xE8re2023code"
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.12950'}]
tags: [Applications, Reinforcement Learning]
---
We release Code Llama, a family of large language models for code based on
Llama 2 providing state-of-the-art performance among open models, infilling
capabilities, support for large input contexts, and zero-shot instruction
following ability for programming tasks. We provide multiple flavors to cover a
wide range of applications: foundation models (Code Llama), Python
specializations (Code Llama - Python), and instruction-following models (Code
Llama - Instruct) with 7B, 13B, 34B and 70B parameters each. All models are
trained on sequences of 16k tokens and show improvements on inputs with up to
100k tokens. 7B, 13B and 70B Code Llama and Code Llama - Instruct variants
support infilling based on surrounding content. Code Llama reaches
state-of-the-art performance among open models on several code benchmarks, with
scores of up to 67% and 65% on HumanEval and MBPP, respectively. Notably, Code
Llama - Python 7B outperforms Llama 2 70B on HumanEval and MBPP, and all our
models outperform every other publicly available model on MultiPL-E. We release
Code Llama under a permissive license that allows for both research and
commercial use.