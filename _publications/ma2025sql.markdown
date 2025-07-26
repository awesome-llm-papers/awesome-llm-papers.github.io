---
layout: publication
title: 'SQL-R1: Training Natural Language To SQL Reasoning Model By Reinforcement
  Learning'
authors: Peixian Ma, Xialie Zhuang, Chengjin Xu, Xuhui Jiang, Ran Chen, Jian Guo
conference: No Venue
year: 2025
bibkey: ma2025sql
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.08600'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Ma et al.
---
Natural Language to SQL (NL2SQL) enables intuitive interactions with databases by transforming natural language queries into structured SQL statements. Despite recent advancements in enhancing human-computer interaction within database applications, significant challenges persist, particularly regarding the inference performance in complex scenarios involving multi-table joins and nested queries. Current methodologies primarily utilize supervised fine-tuning (SFT) to train the NL2SQL model, which may limit adaptability and interpretability in new environments (e.g., finance and healthcare). In order to enhance the reasoning performance of the NL2SQL model in the above complex situations, we introduce SQL-R1, a novel NL2SQL reasoning model trained by the reinforcement learning (RL) algorithms. We design a specialized RL-based reward function tailored for NL2SQL tasks and discussed the impact of cold start on the effectiveness of intensive training. In addition, we achieve competitive accuracy using only a tiny amount of synthetic NL2SQL data for augmented training and further explore data engineering for RL. In existing experiments, SQL-R1 achieves execution accuracy of 88.6% and 66.6% on the benchmark Spider and BIRD, respectively, only using the 7B base model.

https://huggingface.co/discussions/paper/67fc9e73b2383c63dc413e19