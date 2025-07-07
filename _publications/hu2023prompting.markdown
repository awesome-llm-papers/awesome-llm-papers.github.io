---
layout: publication
title: Prompting Is Not A Substitute For Probability Measurements In Large Language
  Models
authors: Jennifer Hu, Roger Levy
conference: Arxiv
year: 2023
citations: 18
bibkey: hu2023prompting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.13264'}]
tags: [Tools, Prompting]
---
Prompting is now a dominant method for evaluating the linguistic knowledge of
large language models (LLMs). While other methods directly read out models'
probability distributions over strings, prompting requires models to access
this internal information by processing linguistic input, thereby implicitly
testing a new type of emergent ability: metalinguistic judgment. In this study,
we compare metalinguistic prompting and direct probability measurements as ways
of measuring models' linguistic knowledge. Broadly, we find that LLMs'
metalinguistic judgments are inferior to quantities directly derived from
representations. Furthermore, consistency gets worse as the prompt query
diverges from direct measurements of next-word probabilities. Our findings
suggest that negative results relying on metalinguistic prompts cannot be taken
as conclusive evidence that an LLM lacks a particular linguistic
generalization. Our results also highlight the value that is lost with the move
to closed APIs where access to probability distributions is limited.