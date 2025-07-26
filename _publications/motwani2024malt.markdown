---
layout: publication
title: 'MALT: Improving Reasoning With Multi-agent LLM Training'
authors: Sumeet Ramesh Motwani, Chandler Smith, Rocktim Jyoti Das, Markian Rybchuk,
  Philip H. S. Torr, Ivan Laptev, Fabio Pizzati, Ronald Clark, Christian Schroeder
  de Witt
conference: No Venue
year: 2024
bibkey: motwani2024malt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.01928'}]
tags: ["Agentic", "Training Techniques"]
short_authors: Motwani et al.
---
Enabling effective collaboration among LLMs is a crucial step toward developing autonomous systems capable of solving complex problems. While LLMs are typically used as single-model generators, where humans critique and refine their outputs, the potential for jointly-trained collaborative models remains largely unexplored. Despite promising results in multi-agent communication and debate settings, little progress has been made in training models to work together on tasks. In this paper, we present a first step toward "Multi-agent LLM training" (MALT) on reasoning problems. Our approach employs a sequential multi-agent setup with heterogeneous LLMs assigned specialized roles: a generator, verifier, and refinement model iteratively solving problems. We propose a trajectory-expansion-based synthetic data generation process and a credit assignment strategy driven by joint outcome based rewards. This enables our post-training setup to utilize both positive and negative trajectories to autonomously improve each model's specialized capabilities as part of a joint sequential system. We evaluate our approach across MATH, GSM8k, and CQA, where MALT on Llama 3.1 8B models achieves relative improvements of 14.14%, 7.12%, and 9.40% respectively over the same baseline model. This demonstrates an early advance in multi-agent cooperative capabilities for performance on mathematical and common sense reasoning questions. More generally, our work provides a concrete direction for research around multi-agent LLM training approaches.

https://huggingface.co/discussions/paper/67500fdeeac35e016f941dcd