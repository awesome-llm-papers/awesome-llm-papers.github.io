---
layout: publication
title: 'Promptchainer: Chaining Large Language Model Prompts Through Visual Programming'
authors: Tongshuang Wu, Ellen Jiang, Aaron Donsbach, Jeff Gray, Alejandra Molina,
  Michael Terry, Carrie J Cai
conference: CHI Conference on Human Factors in Computing Systems Extended Abstracts
year: 2022
bibkey: wu2022promptchainer
citations: 119
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.06566'}]
tags: ["Applications"]
short_authors: Wu et al.
---
While LLMs can effectively help prototype single ML functionalities, many
real-world applications involve complex tasks that cannot be easily handled via
a single run of an LLM. Recent work has found that chaining multiple LLM runs
together (with the output of one step being the input to the next) can help
users accomplish these more complex tasks, and in a way that is perceived to be
more transparent and controllable. However, it remains unknown what users need
when authoring their own LLM chains -- a key step for lowering the barriers for
non-AI-experts to prototype AI-infused applications. In this work, we explore
the LLM chain authoring process. We conclude from pilot studies find that
chaining requires careful scaffolding for transforming intermediate node
outputs, as well as debugging the chain at multiple granularities; to help with
these needs, we designed PromptChainer, an interactive interface for visually
programming chains. Through case studies with four people, we show that
PromptChainer supports building prototypes for a range of applications, and
conclude with open questions on scaling chains to complex tasks, and supporting
low-fi chain prototyping.