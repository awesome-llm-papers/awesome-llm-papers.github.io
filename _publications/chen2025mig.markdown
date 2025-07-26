---
layout: publication
title: 'MIG: Automatic Data Selection For Instruction Tuning By Maximizing Information
  Gain In Semantic Space'
authors: Yicheng Chen, Yining Li, Kai Hu, Zerun Ma, Haochen Ye, Kai Chen
conference: No Venue
year: 2025
bibkey: chen2025mig
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.13835'}]
tags: ["Datasets", "Fine-Tuning"]
short_authors: Chen et al.
---
Data quality and diversity are key to the construction of effective instruction-tuning datasets. % With the increasing availability of open-source instruction-tuning datasets, it is advantageous to automatically select high-quality and diverse subsets from a vast amount of data. % Existing methods typically prioritize instance quality and use heuristic rules to maintain diversity. % However, this absence of a comprehensive view of the entire collection often leads to suboptimal results. % Moreover, heuristic rules generally focus on distance or clustering within the embedding space, which fails to accurately capture the intent of complex instructions in the semantic space. % To bridge this gap, we propose a unified method for quantifying the information content of datasets. This method models the semantic space by constructing a label graph and quantifies diversity based on the distribution of information within the graph. % Based on such a measurement, we further introduce an efficient sampling method that selects data samples iteratively to Maximize the Information Gain (MIG) in semantic space. % Experiments on various datasets and base models demonstrate that MIG consistently outperforms state-of-the-art methods. % Notably, the model fine-tuned with 5% Tulu3 data sampled by MIG achieves comparable performance to the official SFT model trained on the full dataset, with improvements of +5.73% on AlpacaEval and +6.89% on Wildbench.

https://huggingface.co/discussions/paper/6805b38555d3c792e1a9d155