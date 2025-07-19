---
layout: publication
title: Markovian Transformers For Informative Language Modeling
authors: Viteri et al.
conference: Interspeech 2019
year: 2024
bibkey: viteri2024markovian
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.18988'}]
tags: [Interpretability And Explainability, Training Techniques, Prompting, INTERSPEECH,
  Transformer, Model Architecture, Language Modeling, Reinforcement Learning]
---
Chain-of-Thought (CoT) reasoning often fails to faithfully reflect a language model's underlying decision process. We address this by making CoT text causally essential in a "Markovian" language model, factoring next-token prediction through an intermediate CoT and training it to predict future tokens independently of the original prompt. We formalize this via an "informativeness" objective that quantifies how much a trained CoT improves next-token predictions over a baseline. Using policy gradient, we show that Llama 3.1 8B achieves a 33.2% absolute accuracy improvement on GSM8K. Perturbation tests confirm stronger reliance on the CoT, while cross-model transfers indicate these reasoning traces generalize across interpreters. Our approach enhances both accuracy and interpretability, potentially extending CoT reasoning to arbitrarily long contexts and diverse tasks.