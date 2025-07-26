---
layout: publication
title: 'Synthetic Data (almost) From Scratch: Generalized Instruction Tuning For Language
  Models'
authors: Haoran Li, Qingxiu Dong, Zhengyang Tang, Chaojun Wang, Xingxing Zhang, Haoyang
  Huang, Shaohan Huang, Xiaolong Huang, Zeqiang Huang, Dongdong Zhang, Yuxian Gu,
  Xin Cheng, Xun Wang, Si-qing Chen, Li Dong, Wei Lu, Zhifang Sui, Benyou Wang, Wai
  Lam, Furu Wei
conference: No Venue
year: 2024
bibkey: li2024synthetic
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2402.13064'}]
tags: ["Datasets", "Instruction Following", "Training Techniques"]
short_authors: Li et al.
---
We introduce Generalized Instruction Tuning (called GLAN), a general and scalable method for instruction tuning of Large Language Models (LLMs). Unlike prior work that relies on seed examples or existing datasets to construct instruction tuning data, GLAN exclusively utilizes a pre-curated taxonomy of human knowledge and capabilities as input and generates large-scale synthetic instruction data across all disciplines. Specifically, inspired by the systematic structure in human education system, we build the taxonomy by decomposing human knowledge and capabilities to various fields, sub-fields and ultimately, distinct disciplines semi-automatically, facilitated by LLMs. Subsequently, we generate a comprehensive list of subjects for every discipline and proceed to design a syllabus tailored to each subject, again utilizing LLMs. With the fine-grained key concepts detailed in every class session of the syllabus, we are able to generate diverse instructions with a broad coverage across the entire spectrum of human knowledge and skills. Extensive experiments on large language models (e.g., Mistral) demonstrate that GLAN excels in multiple dimensions from mathematical reasoning, coding, academic exams, logical reasoning to general instruction following without using task-specific training data of these tasks. In addition, GLAN allows for easy customization and new fields or skills can be added by simply incorporating a new node into our taxonomy.

https://huggingface.co/discussions/paper/65d572a1b8c5655c03af446e