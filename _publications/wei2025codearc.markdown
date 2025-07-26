---
layout: publication
title: 'Codearc: Benchmarking Reasoning Capabilities Of LLM Agents For Inductive Program
  Synthesis'
authors: Anjiang Wei, Tarun Suresh, Jiannan Cao, Naveen Kannan, Yuheng Wu, Kai Yan,
  Thiago S. F. X. Teixeira, Ke Wang, Alex Aiken
conference: No Venue
year: 2025
bibkey: wei2025codearc
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67eb71101f8a09c48b2e3bee'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.23145'}]
tags: ["Evaluation"]
short_authors: Wei et al.
---
Inductive program synthesis, or programming by example, requires synthesizing functions from input-output examples that generalize to unseen inputs. While large language model agents have shown promise in programming tasks guided by natural language, their ability to perform inductive program synthesis is underexplored. Existing evaluation protocols rely on static sets of examples and held-out tests, offering no feedback when synthesized functions are incorrect and failing to reflect real-world scenarios such as reverse engineering. We propose CodeARC, the Code Abstraction and Reasoning Challenge, a new evaluation framework where agents interact with a hidden target function by querying it with new inputs, synthesizing candidate functions, and iteratively refining their solutions using a differential testing oracle. This interactive setting encourages agents to perform function calls and self-correction based on feedback. We construct the first large-scale benchmark for general-purpose inductive program synthesis, featuring 1114 functions. Among 18 models evaluated, o3-mini performs best with a success rate of 52.7%, highlighting the difficulty of this task. Fine-tuning LLaMA-3.1-8B-Instruct on curated synthesis traces yields up to a 31% relative performance gain. CodeARC provides a more realistic and challenging testbed for evaluating LLM-based program synthesis and inductive reasoning.

https://huggingface.co/discussions/paper/67eb71101f8a09c48b2e3bee