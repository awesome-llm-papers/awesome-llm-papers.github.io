---
layout: publication
title: 'Self-refine: Iterative Refinement With Self-feedback'
authors: Aman Madaan, Niket Tandon, Prakhar Gupta, Skyler Hallinan, Luyu Gao, Sarah
  Wiegreffe, Uri Alon, Nouha Dziri, Shrimai Prabhumoye, Yiming Yang, Shashank Gupta,
  Bodhisattwa Prasad Majumder, Katherine Hermann, Sean Welleck, Amir Yazdanbakhsh,
  Peter Clark
conference: Arxiv
year: 2023
bibkey: madaan2023self
citations: 151
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.17651'}]
tags: ["Evaluation", "Model Architecture", "Reinforcement Learning", "Training Techniques"]
short_authors: Madaan et al.
---
Like humans, large language models (LLMs) do not always generate the best
output on their first try. Motivated by how humans refine their written text,
we introduce Self-Refine, an approach for improving initial outputs from LLMs
through iterative feedback and refinement. The main idea is to generate an
initial output using an LLMs; then, the same LLMs provides feedback for its
output and uses it to refine itself, iteratively. Self-Refine does not require
any supervised training data, additional training, or reinforcement learning,
and instead uses a single LLM as the generator, refiner, and feedback provider.
We evaluate Self-Refine across 7 diverse tasks, ranging from dialog response
generation to mathematical reasoning, using state-of-the-art (GPT-3.5, ChatGPT,
and GPT-4) LLMs. Across all evaluated tasks, outputs generated with Self-Refine
are preferred by humans and automatic metrics over those generated with the
same LLM using conventional one-step generation, improving by ~20% absolute on
average in task performance. Our work demonstrates that even state-of-the-art
LLMs like GPT-4 can be further improved at test time using our simple,
standalone approach.