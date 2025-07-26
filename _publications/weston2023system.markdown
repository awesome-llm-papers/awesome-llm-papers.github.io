---
layout: publication
title: System 2 Attention (is Something You Might Need Too)
authors: Jason Weston, Sainbayar Sukhbaatar
conference: No Venue
year: 2023
bibkey: weston2023system
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2311.11829'}]
tags: ["Instruction Following", "Model Architecture"]
short_authors: Jason Weston, Sainbayar Sukhbaatar
---
Soft attention in Transformer-based Large Language Models (LLMs) is susceptible to incorporating irrelevant information from the context into its latent representations, which adversely affects next token generations. To help rectify these issues, we introduce System 2 Attention (S2A), which leverages the ability of LLMs to reason in natural language and follow instructions in order to decide what to attend to. S2A regenerates the input context to only include the relevant portions, before attending to the regenerated context to elicit the final response. In experiments, S2A outperforms standard attention-based LLMs on three tasks containing opinion or irrelevant information, QA, math word problems and longform generation, where S2A increases factuality and objectivity, and decreases sycophancy.

https://huggingface.co/discussions/paper/655c2e1cb27f103d7b8eb5d7