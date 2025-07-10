---
layout: publication
title: 'Lawbench: Benchmarking Legal Knowledge Of Large Language Models'
authors: Zhiwei Fei et al.
conference: Proceedings of the 2024 Conference on Empirical Methods in Natural Language
  Processing
year: 2023
citations: 16
bibkey: fei2023benchmarking
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.16289'}, {name: Code,
    url: 'https://github.com/open-compass/LawBench/'}]
tags: [Has Code, Model Architecture, GPT, Fine-Tuning, Reinforcement Learning, Training
    Techniques, Evaluation]
---
Large language models (LLMs) have demonstrated strong capabilities in various
aspects. However, when applying them to the highly specialized, safe-critical
legal domain, it is unclear how much legal knowledge they possess and whether
they can reliably perform legal-related tasks. To address this gap, we propose
a comprehensive evaluation benchmark LawBench. LawBench has been meticulously
crafted to have precise assessment of the LLMs' legal capabilities from three
cognitive levels: (1) Legal knowledge memorization: whether LLMs can memorize
needed legal concepts, articles and facts; (2) Legal knowledge understanding:
whether LLMs can comprehend entities, events and relationships within legal
text; (3) Legal knowledge applying: whether LLMs can properly utilize their
legal knowledge and make necessary reasoning steps to solve realistic legal
tasks. LawBench contains 20 diverse tasks covering 5 task types: single-label
classification (SLC), multi-label classification (MLC), regression, extraction
and generation. We perform extensive evaluations of 51 LLMs on LawBench,
including 20 multilingual LLMs, 22 Chinese-oriented LLMs and 9 legal specific
LLMs. The results show that GPT-4 remains the best-performing LLM in the legal
domain, surpassing the others by a significant margin. While fine-tuning LLMs
on legal specific text brings certain improvements, we are still a long way
from obtaining usable and reliable LLMs in legal tasks. All data, model
predictions and evaluation code are released in
https://github.com/open-compass/LawBench/. We hope this benchmark provides
in-depth understanding of the LLMs' domain-specified capabilities and speed up
the development of LLMs in the legal domain.