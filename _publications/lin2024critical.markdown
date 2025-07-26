---
layout: publication
title: 'Critical Tokens Matter: Token-level Contrastive Estimation Enhence Llm''s
  Reasoning Capability'
authors: Zicheng Lin, Tian Liang, Jiahao Xu, Xing Wang, Ruilin Luo, Chufan Shi, Siheng
  Li, Yujiu Yang, Zhaopeng Tu
conference: No Venue
year: 2024
bibkey: lin2024critical
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/674d9e3d0912639dc496af73'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2411.19943'}]
tags: ["Reinforcement Learning"]
short_authors: Lin et al.
---
Large Language Models (LLMs) have exhibited remarkable performance on reasoning tasks. They utilize autoregressive token generation to construct reasoning trajectories, enabling the development of a coherent chain of thought. In this work, we explore the impact of individual tokens on the final outcomes of reasoning tasks. We identify the existence of ``critical tokens'' that lead to incorrect reasoning trajectories in LLMs. Specifically, we find that LLMs tend to produce positive outcomes when forced to decode other tokens instead of critical tokens. Motivated by this observation, we propose a novel approach - cDPO - designed to automatically recognize and conduct token-level rewards for the critical tokens during the alignment process. Specifically, we develop a contrastive estimation approach to automatically identify critical tokens. It is achieved by comparing the generation likelihood of positive and negative models. To achieve this, we separately fine-tune the positive and negative models on various reasoning trajectories, consequently, they are capable of identifying identify critical tokens within incorrect trajectories that contribute to erroneous outcomes. Moreover, to further align the model with the critical token information during the alignment process, we extend the conventional DPO algorithms to token-level DPO and utilize the differential likelihood from the aforementioned positive and negative model as important weight for token-level DPO learning.Experimental results on GSM8K and MATH500 benchmarks with two-widely used models Llama-3 (8B and 70B) and deepseek-math (7B) demonstrate the effectiveness of the propsoed approach cDPO.

https://huggingface.co/discussions/paper/674d9e3d0912639dc496af73