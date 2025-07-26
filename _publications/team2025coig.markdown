---
layout: publication
title: 'COIG-P: A High-quality And Large-scale Chinese Preference Dataset For Alignment
  With Human Values'
authors: M-a-p Team, Siwei Wu, Jincheng Ren, Xinrun Du, Shuyue Guo, Xingwei Qu, Yiming
  Liang, Jie Liu, Yunwen Li, Tianyu Zheng, Boyu Feng, Huaqing Yuan, Zenith Wang, Jiaheng
  Liu, Wenhao Huang, Chenglin Cai, Haoran Que, Jian Yang, Yuelin Bai, Zekun Moore
  Wang, Zhouliang Yu, Qunshu Lin, Ding Pan, Yuchen Jiang, Tiannan Wang, Wangchunshu
  Zhou, Shenzhi Wang, Xingyuan Bu, Minghao Liu, Guoyin Wang, Ge Zhang, Chenghua Lin
conference: No Venue
year: 2025
bibkey: team2025coig
additional_links: [{name: Code, url: 'https://github.com/multimodal-art-projection/COIG-P'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67f6300b1aed1b4344b57cd0'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.05535'}]
tags: ["Datasets"]
short_authors: Team et al.
---
Aligning large language models (LLMs) with human preferences has achieved remarkable success. However, existing Chinese preference datasets are limited by small scale, narrow domain coverage, and lack of rigorous data validation. Additionally, the reliance on human annotators for instruction and response labeling significantly constrains the scalability of human preference datasets. To address these challenges, we design an LLM-based Chinese preference dataset annotation pipeline with no human intervention. Specifically, we crawled and carefully filtered 92k high-quality Chinese queries and employed 15 mainstream LLMs to generate and score chosen-rejected response pairs. Based on it, we introduce COIG-P (Chinese Open Instruction Generalist - Preference), a high-quality, large-scale Chinese preference dataset, comprises 1,009k Chinese preference pairs spanning 6 diverse domains: Chat, Code, Math, Logic, Novel, and Role. Building upon COIG-P, to reduce the overhead of using LLMs for scoring, we trained a 8B-sized Chinese Reward Model (CRM) and meticulously constructed a Chinese Reward Benchmark (CRBench). Evaluation results based on AlignBench liu2024alignbenchbenchmarkingchinesealignment show that that COIG-P significantly outperforms other Chinese preference datasets, and it brings significant performance improvements ranging from 2% to 12% for the Qwen2/2.5 and Infinity-Instruct-3M-0625 model series, respectively. The results on CRBench demonstrate that our CRM has a strong and robust scoring ability. We apply it to filter chosen-rejected response pairs in a test split of COIG-P, and our experiments show that it is comparable to GPT-4o in identifying low-quality samples while maintaining efficiency and cost-effectiveness. Our codes and data are released in https://github.com/multimodal-art-projection/COIG-P.

https://huggingface.co/discussions/paper/67f6300b1aed1b4344b57cd0