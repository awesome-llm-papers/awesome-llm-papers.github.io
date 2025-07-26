---
layout: publication
title: 'Codefusion: A Pre-trained Diffusion Model For Code Generation'
authors: "Mukul Singh, Jos\xE9 Cambronero, Sumit Gulwani, Vu Le, Carina Negreanu,\
  \ Gust Verbruggen"
conference: No Venue
year: 2023
bibkey: singh2023codefusion
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/653f192eec992c5c209bab7e'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2310.17680'}]
tags: ["Llm For Code"]
short_authors: Singh et al.
---
Imagine a developer who can only change their last line of code, how often would they have to start writing a function from scratch before it is correct? Auto-regressive models for code generation from natural language have a similar limitation: they do not easily allow reconsidering earlier tokens generated. We introduce CodeFusion, a pre-trained diffusion code generation model that addresses this limitation by iteratively denoising a complete program conditioned on the encoded natural language. We evaluate CodeFusion on the task of natural language to code generation for Bash, Python, and Microsoft Excel conditional formatting (CF) rules. Experiments show that CodeFusion (75M parameters) performs on par with state-of-the-art auto-regressive systems (350M-175B parameters) in top-1 accuracy and outperforms them in top-3 and top-5 accuracy due to its better balance in diversity versus quality.

https://huggingface.co/discussions/paper/653f192eec992c5c209bab7e