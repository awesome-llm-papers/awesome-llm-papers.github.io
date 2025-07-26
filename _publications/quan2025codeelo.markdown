---
layout: publication
title: 'Codeelo: Benchmarking Competition-level Code Generation Of Llms With Human-comparable
  Elo Ratings'
authors: Shanghaoran Quan, Jiaxi Yang, Bowen Yu, Bo Zheng, Dayiheng Liu, An Yang,
  Xuancheng Ren, Bofei Gao, Yibo Miao, Yunlong Feng, Zekun Wang, Jian Yang, Zeyu Cui,
  Yang Fan, Yichang Zhang, Binyuan Hui, Junyang Lin
conference: No Venue
year: 2025
bibkey: quan2025codeelo
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67775160ab01c44c478e5259'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2501.01257'}]
tags: ["Evaluation", "Llm For Code", "Tools"]
short_authors: Quan et al.
---
With the increasing code reasoning capabilities of existing large language models (LLMs) and breakthroughs in reasoning models like OpenAI o1 and o3, there is a growing need to develop more challenging and comprehensive benchmarks that effectively test their sophisticated competition-level coding abilities. Existing benchmarks, like LiveCodeBench and USACO, fall short due to the unavailability of private test cases, lack of support for special judges, and misaligned execution environments. To bridge this gap, we introduce CodeElo, a standardized competition-level code generation benchmark that effectively addresses all these challenges for the first time. CodeElo benchmark is mainly based on the official CodeForces platform and tries to align with the platform as much as possible. We compile the recent six months of contest problems on CodeForces with detailed information such as contest divisions, problem difficulty ratings, and problem algorithm tags. We introduce a unique judging method in which problems are submitted directly to the platform and develop a reliable Elo rating calculation system that aligns with the platform and is comparable with human participants but has lower variance. By testing on our CodeElo, we provide the Elo ratings of 30 existing popular open-source and 3 proprietary LLMs for the first time. The results show that o1-mini and QwQ-32B-Preview stand out significantly, achieving Elo ratings of 1578 and 1261, respectively, while other models struggle even with the easiest problems, placing in the lowest 20 percent among all human participants. Detailed analysis experiments are also conducted to provide insights into performance across algorithms and comparisons between using C++ and Python, which can suggest directions for future studies.

https://huggingface.co/discussions/paper/67775160ab01c44c478e5259