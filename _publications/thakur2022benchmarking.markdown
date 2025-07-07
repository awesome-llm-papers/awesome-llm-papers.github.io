---
layout: publication
title: Benchmarking Large Language Models For Automated Verilog RTL Code Generation
authors: Shailja Thakur et al.
conference: Arxiv
year: 2022
citations: 65
bibkey: thakur2022benchmarking
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.11140'}, {name: Code,
    url: 'https://github.com/shailja-thakur/VGen'}]
tags: [Training Techniques, Merging, Fine-Tuning, Tools, Has Code]
---
Automating hardware design could obviate a significant amount of human error
from the engineering process and lead to fewer errors. Verilog is a popular
hardware description language to model and design digital systems, thus
generating Verilog code is a critical first step. Emerging large language
models (LLMs) are able to write high-quality code in other programming
languages. In this paper, we characterize the ability of LLMs to generate
useful Verilog. For this, we fine-tune pre-trained LLMs on Verilog datasets
collected from GitHub and Verilog textbooks. We construct an evaluation
framework comprising test-benches for functional analysis and a flow to test
the syntax of Verilog code generated in response to problems of varying
difficulty. Our findings show that across our problem scenarios, the
fine-tuning results in LLMs more capable of producing syntactically correct
code (25.9% overall). Further, when analyzing functional correctness, a
fine-tuned open-source CodeGen LLM can outperform the state-of-the-art
commercial Codex LLM (6.5% overall). Training/evaluation scripts and LLM
checkpoints are available: https://github.com/shailja-thakur/VGen.