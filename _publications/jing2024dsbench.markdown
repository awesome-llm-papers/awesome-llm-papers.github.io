---
layout: publication
title: 'Dsbench: How Far Are Data Science Agents To Becoming Data Science Experts?'
authors: Liqiang Jing, Zhehui Huang, Xiaoyang Wang, Wenlin Yao, Wenhao Yu, Kaixin
  Ma, Hongming Zhang, Xinya Du, Dong Yu
conference: No Venue
year: 2024
bibkey: jing2024dsbench
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/66e4032f8bcd43ff6cdfd835'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2409.07703'}]
tags: ["Agentic", "Applications"]
short_authors: Jing et al.
---
Large Language Models (LLMs) and Large Vision-Language Models (LVLMs) have demonstrated impressive language/vision reasoning abilities, igniting the recent trend of building agents for targeted applications such as shopping assistants or AI software engineers. Recently, many data science benchmarks have been proposed to investigate their performance in the data science domain. However, existing data science benchmarks still fall short when compared to real-world data science applications due to their simplified settings. To bridge this gap, we introduce DSBench, a comprehensive benchmark designed to evaluate data science agents with realistic tasks. This benchmark includes 466 data analysis tasks and 74 data modeling tasks, sourced from Eloquence and Kaggle competitions. DSBench offers a realistic setting by encompassing long contexts, multimodal task backgrounds, reasoning with large data files and multi-table structures, and performing end-to-end data modeling tasks. Our evaluation of state-of-the-art LLMs, LVLMs, and agents shows that they struggle with most tasks, with the best agent solving only 34.12% of data analysis tasks and achieving a 34.74% Relative Performance Gap (RPG). These findings underscore the need for further advancements in developing more practical, intelligent, and autonomous data science agents.

https://huggingface.co/discussions/paper/66e4032f8bcd43ff6cdfd835