---
layout: publication
title: 'MAGE: A Multi-agent Engine For Automated RTL Code Generation'
authors: Zhao et al.
conference: 2023 Design, Automation &amp; Test in Europe Conference &amp; Exhibition
  (DATE)
year: 2024
bibkey: zhao2024mage
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.07822'}]
tags: [Agentic, Evaluation, Reinforcement Learning, Datasets, LLM For Code]
---
The automatic generation of RTL code (e.g., Verilog) through natural language
instructions has emerged as a promising direction with the advancement of large
language models (LLMs). However, producing RTL code that is both syntactically
and functionally correct remains a significant challenge. Existing
single-LLM-agent approaches face substantial limitations because they must
navigate between various programming languages and handle intricate generation,
verification, and modification tasks. To address these challenges, this paper
introduces MAGE, the first open-source multi-agent AI system designed for
robust and accurate Verilog RTL code generation. We propose a novel
high-temperature RTL candidate sampling and debugging system that effectively
explores the space of code candidates and significantly improves the quality of
the candidates. Furthermore, we design a novel Verilog-state checkpoint
checking mechanism that enables early detection of functional errors and
delivers precise feedback for targeted fixes, significantly enhancing the
functional correctness of the generated RTL code. MAGE achieves a 95.7% rate of
syntactic and functional correctness code generation on VerilogEval-Human 2
benchmark, surpassing the state-of-the-art Claude-3.5-sonnet by 23.3 %,
demonstrating a robust and reliable approach for AI-driven RTL design
workflows.