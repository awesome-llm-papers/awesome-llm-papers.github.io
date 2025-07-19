---
layout: publication
title: 'Socratic-mcts: Test-time Visual Reasoning By Asking The Right Questions'
authors: Acuna et al.
conference: PLoS Neglected Tropical Diseases
year: 2025
bibkey: acuna2025socratic
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.08927'}]
tags: [RAG, Training Techniques, Distillation, Agentic, Evaluation, Efficiency And
    Optimization, Reinforcement Learning, Multimodal Models, Datasets]
---
Recent research in vision-language models (VLMs) has centered around the possibility of equipping them with implicit long-form chain-of-thought reasoning -- akin to the success observed in language models -- via distillation and reinforcement learning. But what about the non-reasoning models already trained and deployed across the internet? Should we simply abandon them, or is there hope for a search mechanism that can elicit hidden knowledge and induce long reasoning traces -- without any additional training or supervision? In this paper, we explore this possibility using a Monte Carlo Tree Search (MCTS)-inspired algorithm, which injects subquestion-subanswer pairs into the model's output stream. We show that framing reasoning as a search process -- where subquestions act as latent decisions within a broader inference trajectory -- helps the model "connect the dots" between fragmented knowledge and produce extended reasoning traces in non-reasoning models. We evaluate our method across three benchmarks and observe consistent improvements. Notably, our approach yields a 2% overall improvement on MMMU-PRO, including a significant 9% gain in Liberal Arts.