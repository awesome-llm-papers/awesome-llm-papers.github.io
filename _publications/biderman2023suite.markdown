---
layout: publication
title: 'Pythia: A Suite For Analyzing Large Language Models Across Training And Scaling'
authors: Stella Biderman et al.
conference: Arxiv
year: 2023
citations: 94
bibkey: biderman2023suite
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2304.01373v2'}, {name: Code,
    url: 'https://github.com/EleutherAI/pythia'}]
tags: [Has Code, Ethics and Bias, Few-Shot, Tools, Training Techniques]
---
How do large language models (LLMs) develop and evolve over the course of
training? How do these patterns change as models scale? To answer these
questions, we introduce \textit\{Pythia\}, a suite of 16 LLMs all trained on
public data seen in the exact same order and ranging in size from 70M to 12B
parameters. We provide public access to 154 checkpoints for each one of the 16
models, alongside tools to download and reconstruct their exact training
dataloaders for further study. We intend \textit\{Pythia\} to facilitate research
in many areas, and we present several case studies including novel results in
memorization, term frequency effects on few-shot performance, and reducing
gender bias. We demonstrate that this highly controlled setup can be used to
yield novel insights toward LLMs and their training dynamics. Trained models,
analysis code, training code, and training data can be found at
https://github.com/EleutherAI/pythia.