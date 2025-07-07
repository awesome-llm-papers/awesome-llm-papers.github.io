---
layout: publication
title: 'Logic-lm: Empowering Large Language Models With Symbolic Solvers For Faithful
  Logical Reasoning'
authors: Liangming Pan, Alon Albalak, Xinyi Wang, William Yang Wang
conference: Arxiv
year: 2023
citations: 26
bibkey: pan2023logic
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.12295'}, {name: Code,
    url: 'https://github.com/teacherpeterpan/Logic-LLM'}]
tags: [RAG, Has Code, Tools, Prompting]
---
Large Language Models (LLMs) have shown human-like reasoning abilities but
still struggle with complex logical problems. This paper introduces a novel
framework, Logic-LM, which integrates LLMs with symbolic solvers to improve
logical problem-solving. Our method first utilizes LLMs to translate a natural
language problem into a symbolic formulation. Afterward, a deterministic
symbolic solver performs inference on the formulated problem. We also introduce
a self-refinement module, which utilizes the symbolic solver's error messages
to revise symbolic formalizations. We demonstrate Logic-LM's effectiveness on
five logical reasoning datasets: ProofWriter, PrOntoQA, FOLIO,
LogicalDeduction, and AR-LSAT. On average, Logic-LM achieves a significant
performance boost of 39.2% over using LLM alone with standard prompting and
18.4% over LLM with chain-of-thought prompting. Our findings suggest that
Logic-LM, by combining LLMs with symbolic logic, offers a promising avenue for
faithful logical reasoning. Code and data are publicly available at
https://github.com/teacherpeterpan/Logic-LLM.