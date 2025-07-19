---
layout: publication
title: Do Prompt Patterns Affect Code Quality? A First Empirical Assessment Of Chatgpt-generated
  Code
authors: Della Porta Antonio, Lambiase Stefano, Palomba Fabio
conference: ACM Transactions on Software Engineering and Methodology
year: 2025
bibkey: dellaporta2025do
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.13656'}]
tags: [Security, Model Architecture, Prompting, Tools, Evaluation, LLM For Code, Few
    Shot, LLM for Code, GPT, Datasets]
---
Large Language Models (LLMs) have rapidly transformed software development,
especially in code generation. However, their inconsistent performance, prone
to hallucinations and quality issues, complicates program comprehension and
hinders maintainability. Research indicates that prompt engineering-the
practice of designing inputs to direct LLMs toward generating relevant
outputs-may help address these challenges. In this regard, researchers have
introduced prompt patterns, structured templates intended to guide users in
formulating their requests. However, the influence of prompt patterns on code
quality has yet to be thoroughly investigated. An improved understanding of
this relationship would be essential to advancing our collective knowledge on
how to effectively use LLMs for code generation, thereby enhancing their
understandability in contemporary software development. This paper empirically
investigates the impact of prompt patterns on code quality, specifically
maintainability, security, and reliability, using the Dev-GPT dataset. Results
show that Zero-Shot prompting is most common, followed by Zero-Shot with
Chain-of-Thought and Few-Shot. Analysis of 7583 code files across quality
metrics revealed minimal issues, with Kruskal-Wallis tests indicating no
significant differences among patterns, suggesting that prompt structure may
not substantially impact these quality metrics in ChatGPT-assisted code
generation.