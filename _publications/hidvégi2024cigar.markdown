---
layout: publication
title: 'Cigar: Cost-efficient Program Repair With Llms'
authors: "Hidv\xE9gi et al."
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2024
bibkey: "hidv\xE9gi2024cigar"
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.06598'}]
tags: [RAG, Prompting, AAAI, Datasets, LLM For Code]
---
Large language models (LLM) have proven to be effective at automated program
repair (APR). However, using LLMs can be costly, with companies invoicing users
by the number of tokens. In this paper, we propose CigaR, the first LLM-based
APR tool that focuses on minimizing the repair cost. CigaR works in two major
steps: generating a first plausible patch and multiplying plausible patches.
CigaR optimizes the prompts and the prompt setting to maximize the information
given to LLMs using the smallest possible number of tokens. Our experiments on
429 bugs from the widely used Defects4J and HumanEval-Java datasets shows that
CigaR reduces the token cost by 73%. On average, CigaR spends 127k tokens per
bug while the baseline uses 467k tokens per bug. On the subset of bugs that are
fixed by both, CigaR spends 20k per bug while the baseline uses 608k tokens, a
cost saving of 96%. Our extensive experiments show that CigaR is a
cost-effective LLM-based program repair tool that uses a low number of tokens
to automatically generate patches.