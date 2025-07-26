---
layout: publication
title: 'Tablegpt: Towards Unifying Tables, Nature Language And Commands Into One GPT'
authors: Liangyu Zha, Junlin Zhou, Liyao Li, Rui Wang, Qingyi Huang, Saisai Yang,
  Jing Yuan, Changbao Su, Xiang Li, Aofeng Su, Tao Zhang, Chen Zhou, Kaizhe Shou,
  Miao Wang, Wufang Zhu, Guoshan Lu, Chao Ye, Yali Ye, Wentao Ye, Yiming Zhang, Xinglong
  Deng, Jie Xu, Haobo Wang, Gang Chen, Junbo Zhao
conference: No Venue
year: 2023
bibkey: zha2023tablegpt
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/64b6197cc1452d75f357687e'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2307.08674'}]
tags: ["Applications", "Model Architecture", "Tools"]
short_authors: Zha et al.
---
Tables are prevalent in real-world databases, requiring significant time and effort for humans to analyze and manipulate. The advancements in large language models (LLMs) have made it possible to interact with tables using natural language input, bringing this capability closer to reality. In this paper, we present TableGPT, a unified fine-tuned framework that enables LLMs to understand and operate on tables using external functional commands. It introduces the capability to seamlessly interact with tables, enabling a wide range of functionalities such as question answering, data manipulation (e.g., insert, delete, query, and modify operations), data visualization, analysis report generation, and automated prediction. TableGPT aims to provide convenience and accessibility to users by empowering them to effortlessly leverage tabular data. At the core of TableGPT lies the novel concept of global tabular representations, which empowers LLMs to gain a comprehensive understanding of the entire table beyond meta-information. By jointly training LLMs on both table and text modalities, TableGPT achieves a deep understanding of tabular data and the ability to perform complex operations on tables through chain-of-command instructions. Importantly, TableGPT offers the advantage of being a self-contained system rather than relying on external API interfaces. Moreover, it supports efficient data process flow, query rejection (when appropriate) and private deployment, enabling faster domain data fine-tuning and ensuring data privacy, which enhances the framework's adaptability to specific use cases.

https://huggingface.co/discussions/paper/64b6197cc1452d75f357687e