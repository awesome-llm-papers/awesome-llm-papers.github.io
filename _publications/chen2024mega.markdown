---
layout: publication
title: 'Mega-bench: Scaling Multimodal Evaluation To Over 500 Real-world Tasks'
authors: Jiacheng Chen, Tianhao Liang, Sherman Siu, Zhengqing Wang, Kai Wang, Yubo
  Wang, Yuansheng Ni, Wang Zhu, Ziyan Jiang, Bohan Lyu, Dongfu Jiang, Xuan He, Yuan
  Liu, Hexiang Hu, Xiang Yue, Wenhu Chen
conference: No Venue
year: 2024
bibkey: chen2024mega
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/670dd83085a1548f5cdf9a80'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.10563'}]
tags: ["Applications", "Evaluation"]
short_authors: Chen et al.
---
We present MEGA-Bench, an evaluation suite that scales multimodal evaluation to over 500 real-world tasks, to address the highly heterogeneous daily use cases of end users. Our objective is to optimize for a set of high-quality data samples that cover a highly diverse and rich set of multimodal tasks, while enabling cost-effective and accurate model evaluation. In particular, we collected 505 realistic tasks encompassing over 8,000 samples from 16 expert annotators to extensively cover the multimodal task space. Instead of unifying these problems into standard multi-choice questions (like MMMU, MMBench, and MMT-Bench), we embrace a wide range of output formats like numbers, phrases, code, \LaTeX, coordinates, JSON, free-form, etc. To accommodate these formats, we developed over 40 metrics to evaluate these tasks. Unlike existing benchmarks, MEGA-Bench offers a fine-grained capability report across multiple dimensions (e.g., application, input type, output format, skill), allowing users to interact with and visualize model capabilities in depth. We evaluate a wide variety of frontier vision-language models on MEGA-Bench to understand their capabilities across these dimensions.

https://huggingface.co/discussions/paper/670dd83085a1548f5cdf9a80