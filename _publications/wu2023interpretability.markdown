---
layout: publication
title: 'Interpretability At Scale: Identifying Causal Mechanisms In Alpaca'
authors: Wu et al.
conference: 'Journal of the Royal Statistical Society Series A: Statistics in Society'
year: 2023
bibkey: wu2023interpretability
citations: 276
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.08809'}]
tags: [Interpretability And Explainability, Reinforcement Learning, Training Techniques,
  Responsible AI]
---
Obtaining human-interpretable explanations of large, general-purpose language
models is an urgent goal for AI safety. However, it is just as important that
our interpretability methods are faithful to the causal dynamics underlying
model behavior and able to robustly generalize to unseen inputs. Distributed
Alignment Search (DAS) is a powerful gradient descent method grounded in a
theory of causal abstraction that has uncovered perfect alignments between
interpretable symbolic algorithms and small deep learning models fine-tuned for
specific tasks. In the present paper, we scale DAS significantly by replacing
the remaining brute-force search steps with learned parameters -- an approach
we call Boundless DAS. This enables us to efficiently search for interpretable
causal structure in large language models while they follow instructions. We
apply Boundless DAS to the Alpaca model (7B parameters), which, off the shelf,
solves a simple numerical reasoning problem. With Boundless DAS, we discover
that Alpaca does this by implementing a causal model with two interpretable
boolean variables. Furthermore, we find that the alignment of neural
representations with these variables is robust to changes in inputs and
instructions. These findings mark a first step toward faithfully understanding
the inner-workings of our ever-growing and most widely deployed language
models. Our tool is extensible to larger LLMs and is released publicly at
`https://github.com/stanfordnlp/pyvene`.