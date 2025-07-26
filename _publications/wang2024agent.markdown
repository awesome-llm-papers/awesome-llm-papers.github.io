---
layout: publication
title: Agent Workflow Memory
authors: Zora Zhiruo Wang, Jiayuan Mao, Daniel Fried, Graham Neubig
conference: No Venue
year: 2024
bibkey: wang2024agent
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2409.07429'}]
tags: ["Agentic"]
short_authors: Wang et al.
---
Despite the potential of language model-based agents to solve real-world tasks such as web navigation, current methods still struggle with long-horizon tasks with complex action trajectories. In contrast, humans can flexibly solve complex tasks by learning reusable task workflows from past experiences and using them to guide future actions. To build agents that can similarly benefit from this process, we introduce Agent Workflow Memory (AWM), a method for inducing commonly reused routines, i.e., workflows, and selectively providing workflows to the agent to guide subsequent generations. AWM flexibly applies to both offline and online scenarios, where agents induce workflows from training examples beforehand or from test queries on the fly. We experiment on two major web navigation benchmarks -- Mind2Web and WebArena -- that collectively cover 1000+ tasks from 200+ domains across travel, shopping, and social media, among others. AWM substantially improves the baseline results by 24.6% and 51.1% relative success rate on Mind2Web and WebArena while reducing the number of steps taken to solve WebArena tasks successfully. Furthermore, online AWM robustly generalizes in cross-task, website, and domain evaluations, surpassing baselines from 8.9 to 14.0 absolute points as train-test task distribution gaps widen.

https://huggingface.co/discussions/paper/66e254c524df851611e7f5ef