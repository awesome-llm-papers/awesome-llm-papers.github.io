---
layout: publication
title: Mixture-of-agents Enhances Large Language Model Capabilities
authors: Junlin Wang, Jue Wang, Ben Athiwaratkun, Ce Zhang, James Zou
conference: No Venue
year: 2024
bibkey: wang2024mixture
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2406.04692'}]
tags: ["Agentic", "Model Architecture"]
short_authors: Wang et al.
---
Recent advances in large language models (LLMs) demonstrate substantial capabilities in natural language understanding and generation tasks. With the growing number of LLMs, how to harness the collective expertise of multiple LLMs is an exciting open direction. Toward this goal, we propose a new approach that leverages the collective strengths of multiple LLMs through a Mixture-of-Agents (MoA) methodology. In our approach, we construct a layered MoA architecture wherein each layer comprises multiple LLM agents. Each agent takes all the outputs from agents in the previous layer as auxiliary information in generating its response. MoA models achieves state-of-art performance on AlpacaEval 2.0, MT-Bench and FLASK, surpassing GPT-4 Omni. For example, our MoA using only open-source LLMs is the leader of AlpacaEval 2.0 by a substantial gap, achieving a score of 65.1% compared to 57.5% by GPT-4 Omni.

https://huggingface.co/discussions/paper/66665d63628a6ad02e599dd3