---
layout: publication
title: 'Beyond Chinchilla-optimal: Accounting For Inference In Language Model Scaling
  Laws'
authors: Nikhil Sardana, Jonathan Frankle
conference: No Venue
year: 2023
bibkey: sardana2023beyond
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2401.00448'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Nikhil Sardana, Jonathan Frankle
---
Large language model (LLM) scaling laws are empirical formulas that estimate changes in model quality as a result of increasing parameter count and training data. However, these formulas, including the popular DeepMind Chinchilla scaling laws, neglect to include the cost of inference. We modify the Chinchilla scaling laws to calculate the optimal LLM parameter count and pre-training data size to train and deploy a model of a given quality and inference demand. We conduct our analysis both in terms of a compute budget and real-world costs and find that LLM researchers expecting reasonably large inference demand (~1B requests) should train models smaller and longer than Chinchilla-optimal.

https://huggingface.co/discussions/paper/65938e55dbdeb5bf078f5661