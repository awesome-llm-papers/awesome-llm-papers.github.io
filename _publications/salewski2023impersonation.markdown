---
layout: publication
title: In-context Impersonation Reveals Large Language Models' Strengths And Biases
authors: Leonard Salewski, Stephan Alaniz, Isabel Rio-torto, Eric Schulz, Zeynep Akata
conference: Arxiv
year: 2023
citations: 23
bibkey: salewski2023impersonation
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.14930'}]
tags: [Ethics and Bias, Fine-Tuning, Prompting]
---
In everyday conversations, humans can take on different roles and adapt their
vocabulary to their chosen roles. We explore whether LLMs can take on, that is
impersonate, different roles when they generate text in-context. We ask LLMs to
assume different personas before solving vision and language tasks. We do this
by prefixing the prompt with a persona that is associated either with a social
identity or domain expertise. In a multi-armed bandit task, we find that LLMs
pretending to be children of different ages recover human-like developmental
stages of exploration. In a language-based reasoning task, we find that LLMs
impersonating domain experts perform better than LLMs impersonating non-domain
experts. Finally, we test whether LLMs' impersonations are complementary to
visual information when describing different categories. We find that
impersonation can improve performance: an LLM prompted to be a bird expert
describes birds better than one prompted to be a car expert. However,
impersonation can also uncover LLMs' biases: an LLM prompted to be a man
describes cars better than one prompted to be a woman. These findings
demonstrate that LLMs are capable of taking on diverse roles and that this
in-context impersonation can be used to uncover their hidden strengths and
biases.