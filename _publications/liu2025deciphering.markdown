---
layout: publication
title: 'Deciphering Trajectory-aided LLM Reasoning: An Optimization Perspective'
authors: Junnan Liu, Hongwei Liu, Linchen Xiao, Shudong Liu, Taolin Zhang, Zihan Ma,
  Songyang Zhang, Kai Chen
conference: No Venue
year: 2025
bibkey: liu2025deciphering
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.19815'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Liu et al.
---
We propose a novel framework for comprehending the reasoning capabilities of large language models (LLMs) through the perspective of meta-learning. By conceptualizing reasoning trajectories as pseudo-gradient descent updates to the LLM's parameters, we identify parallels between LLM reasoning and various meta-learning paradigms. We formalize the training process for reasoning tasks as a meta-learning setup, with each question treated as an individual task, and reasoning trajectories serving as the inner loop optimization for adapting model parameters. Once trained on a diverse set of questions, the LLM develops fundamental reasoning capabilities that can generalize to previously unseen questions. Extensive empirical evaluations substantiate the strong connection between LLM reasoning and meta-learning, exploring several issues of significant interest from a meta-learning standpoint. Our work not only enhances the understanding of LLM reasoning but also provides practical insights for improving these models through established meta-learning techniques.

https://huggingface.co/discussions/paper/683523b41a2911c0774a1e78