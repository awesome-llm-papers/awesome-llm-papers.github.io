---
layout: publication
title: 'Ignore Previous Prompt: Attack Techniques For Language Models'
authors: "Perez F\xE1bio, Ribeiro Ian"
conference: Arxiv
year: 2022
bibkey: perez2022ignore
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.09527'}]
tags: [GPT, Prompting, Agentic, Tools, Transformer, Model Architecture, Applications,
  Security, Merging]
---
Transformer-based large language models (LLMs) provide a powerful foundation
for natural language tasks in large-scale customer-facing applications.
However, studies that explore their vulnerabilities emerging from malicious
user interaction are scarce. By proposing PromptInject, a prosaic alignment
framework for mask-based iterative adversarial prompt composition, we examine
how GPT-3, the most widely deployed language model in production, can be easily
misaligned by simple handcrafted inputs. In particular, we investigate two
types of attacks -- goal hijacking and prompt leaking -- and demonstrate that
even low-aptitude, but sufficiently ill-intentioned agents, can easily exploit
GPT-3's stochastic nature, creating long-tail risks. The code for PromptInject
is available at https://github.com/agencyenterprise/PromptInject.