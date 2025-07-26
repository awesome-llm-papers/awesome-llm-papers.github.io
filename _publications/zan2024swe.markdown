---
layout: publication
title: 'Swe-bench-java: A Github Issue Resolving Benchmark For Java'
authors: Daoguang Zan, Zhirong Huang, Ailun Yu, Shaoxin Lin, Yifan Shi, Wei Liu, Dong
  Chen, Zongshuai Qi, Hao Yu, Lei Yu, Dezhi Ran, Muhan Zeng, Bo Shen, Pan Bian, Guangtai
  Liang, Bei Guan, Pengjie Huang, Tao Xie, Yongji Wang, Qianxiang Wang
conference: No Venue
year: 2024
bibkey: zan2024swe
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/66cd3ae4a7af45d8de3a6380'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2408.14354'}]
tags: ["Evaluation", "Has Code"]
short_authors: Zan et al.
---
GitHub issue resolving is a critical task in software engineering, recently gaining significant attention in both industry and academia. Within this task, SWE-bench has been released to evaluate issue resolving capabilities of large language models (LLMs), but has so far only focused on Python version. However, supporting more programming languages is also important, as there is a strong demand in industry. As a first step toward multilingual support, we have developed a Java version of SWE-bench, called SWE-bench-java. We have publicly released the dataset, along with the corresponding Docker-based evaluation environment and leaderboard, which will be continuously maintained and updated in the coming months. To verify the reliability of SWE-bench-java, we implement a classic method SWE-agent and test several powerful LLMs on it. As is well known, developing a high-quality multi-lingual benchmark is time-consuming and labor-intensive, so we welcome contributions through pull requests or collaboration to accelerate its iteration and refinement, paving the way for fully automated programming.

https://huggingface.co/discussions/paper/66cd3ae4a7af45d8de3a6380