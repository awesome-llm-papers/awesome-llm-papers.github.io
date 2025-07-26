---
layout: publication
title: 'Pythia: A Suite For Analyzing Large Language Models Across Training And Scaling'
authors: Stella Biderman, Hailey Schoelkopf, Quentin Anthony, Herbie Bradley, Kyle
  O'brien, Eric Hallahan, Mohammad Aflah Khan, Shivanshu Purohit, Usvsn Sai Prashanth,
  Edward Raff, Aviya Skowron, Lintang Sutawika, Oskar van Der Wal
conference: Arxiv
year: 2023
bibkey: biderman2023pythia
citations: 97
additional_links: [{name: Code, url: 'https://github.com/EleutherAI/pythia'}, {name: Paper,
    url: 'https://arxiv.org/abs/2304.01373'}]
tags: ["Has Code", "Tools", "Training Techniques"]
short_authors: Biderman et al.
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