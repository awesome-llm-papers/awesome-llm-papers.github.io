---
layout: publication
title: How Language Model Hallucinations Can Snowball
authors: Zhang et al.
conference: Arxiv
year: 2023
bibkey: zhang2023how
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.13534'}]
tags: [Interpretability And Explainability, GPT, Model Architecture, Reinforcement
    Learning, Applications, Datasets]
---
A major risk of using language models in practical applications is their
tendency to hallucinate incorrect statements. Hallucinations are often
attributed to knowledge gaps in LMs, but we hypothesize that in some cases,
when justifying previously generated hallucinations, LMs output false claims
that they can separately recognize as incorrect. We construct three
question-answering datasets where ChatGPT and GPT-4 often state an incorrect
answer and offer an explanation with at least one incorrect claim. Crucially,
we find that ChatGPT and GPT-4 can identify 67% and 87% of their own mistakes,
respectively. We refer to this phenomenon as hallucination snowballing: an LM
over-commits to early mistakes, leading to more mistakes that it otherwise
would not make.