---
layout: publication
title: 'Llm-microscope: Uncovering The Hidden Role Of Punctuation In Context Memory
  Of Transformers'
authors: Anton Razzhigaev, Matvey Mikhalchuk, Temurbek Rahmatullaev, Elizaveta Goncharova,
  Polina Druzhinina, Ivan Oseledets, Andrey Kuznetsov
conference: No Venue
year: 2025
bibkey: razzhigaev2025llm
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67bc1a4c72499ce2ba28cd49'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.15007'}]
tags: ["Evaluation Frameworks"]
short_authors: Razzhigaev et al.
---
We introduce methods to quantify how Large Language Models (LLMs) encode and store contextual information, revealing that tokens often seen as minor (e.g., determiners, punctuation) carry surprisingly high context. Notably, removing these tokens -- especially stopwords, articles, and commas -- consistently degrades performance on MMLU and BABILong-4k, even if removing only irrelevant tokens. Our analysis also shows a strong correlation between contextualization and linearity, where linearity measures how closely the transformation from one layer's embeddings to the next can be approximated by a single linear mapping. These findings underscore the hidden importance of filler tokens in maintaining context. For further exploration, we present LLM-Microscope, an open-source toolkit that assesses token-level nonlinearity, evaluates contextual memory, visualizes intermediate layer contributions (via an adapted Logit Lens), and measures the intrinsic dimensionality of representations. This toolkit illuminates how seemingly trivial tokens can be critical for long-range understanding.

https://huggingface.co/discussions/paper/67bc1a4c72499ce2ba28cd49