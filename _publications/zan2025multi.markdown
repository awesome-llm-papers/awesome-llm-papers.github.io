---
layout: publication
title: 'Multi-swe-bench: A Multilingual Benchmark For Issue Resolving'
authors: Daoguang Zan, Zhirong Huang, Wei Liu, Hanwu Chen, Linhao Zhang, Shulin Xin,
  Lu Chen, Qi Liu, Xiaojian Zhong, Aoyan Li, Siyao Liu, Yongsheng Xiao, Liangqiang
  Chen, Yuyu Zhang, Jing Su, Tianyu Liu, Rui Long, Kai Shen, Liang Xiang
conference: No Venue
year: 2025
bibkey: zan2025multi
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67ef4d93c1e251f239495a9b'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.02605'}]
tags: ["Datasets", "Evaluation"]
short_authors: Zan et al.
---
The task of issue resolving is to modify a codebase to generate a patch that addresses a given issue. However, existing benchmarks, such as SWE-bench, focus almost exclusively on Python, making them insufficient for evaluating Large Language Models (LLMs) across diverse software ecosystems. To address this, we introduce a multilingual issue-resolving benchmark, called Multi-SWE-bench, covering Java, TypeScript, JavaScript, Go, Rust, C, and C++. It includes a total of 1,632 high-quality instances, which were carefully annotated from 2,456 candidates by 68 expert annotators, ensuring that the benchmark can provide an accurate and reliable evaluation. Based on Multi-SWE-bench, we evaluate a series of state-of-the-art models using three representative methods (Agentless, SWE-agent, and OpenHands) and present a comprehensive analysis with key empirical insights. In addition, we launch a Multi-SWE-RL open-source community, aimed at building large-scale reinforcement learning (RL) training datasets for issue-resolving tasks. As an initial contribution, we release a set of 4,723 well-structured instances spanning seven programming languages, laying a solid foundation for RL research in this domain. More importantly, we open-source our entire data production pipeline, along with detailed tutorials, encouraging the open-source community to continuously contribute and expand the dataset. We envision our Multi-SWE-bench and the ever-growing Multi-SWE-RL community as catalysts for advancing RL toward its full potential, bringing us one step closer to the dawn of AGI.

https://huggingface.co/discussions/paper/67ef4d93c1e251f239495a9b