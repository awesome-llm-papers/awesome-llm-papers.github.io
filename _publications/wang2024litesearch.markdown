---
layout: publication
title: 'Litesearch: Efficacious Tree Search For LLM'
authors: Ante Wang, Linfeng Song, Ye Tian, Baolin Peng, Dian Yu, Haitao Mi, Jinsong
  Su, Dong Yu
conference: No Venue
year: 2024
bibkey: wang2024litesearch
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2407.00320'}]
tags: ["Applications", "Datasets"]
short_authors: Wang et al.
---
Recent research suggests that tree search algorithms (e.g. Monte Carlo Tree Search) can dramatically boost LLM performance on complex mathematical reasoning tasks. However, they often require more than 10 times the computational resources of greedy decoding due to wasteful search strategies, making them difficult to be deployed in practical applications. This study introduces a novel guided tree search algorithm with dynamic node selection and node-level exploration budget (maximum number of children) calculation to tackle this issue. By considering the search progress towards the final answer (history) and the guidance from a value network (future) trained without any step-wise annotations, our algorithm iteratively selects the most promising tree node before expanding it within the boundaries of the allocated computational budget. Experiments conducted on the GSM8K and TabMWP datasets demonstrate that our approach not only offers competitive performance but also enjoys significantly lower computational costs compared to baseline methods.

https://huggingface.co/discussions/paper/668371223d01a30be915a7a6