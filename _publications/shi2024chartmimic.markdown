---
layout: publication
title: 'Chartmimic: Evaluating Lmm''s Cross-modal Reasoning Capability Via Chart-to-code
  Generation'
authors: Chufan Shi, Cheng Yang, Yaxin Liu, Bo Shui, Junjie Wang, Mohan Jing, Linran
  Xu, Xinyu Zhu, Siheng Li, Yuxiang Zhang, Gongye Liu, Xiaomei Nie, Deng Cai, Yujiu
  Yang
conference: No Venue
year: 2024
bibkey: shi2024chartmimic
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/666fdf3ec16d62cbb045cb8f'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2406.09961'}]
tags: ["Applications", "Evaluation", "Llm For Code"]
short_authors: Shi et al.
---
We introduce a new benchmark, ChartMimic, aimed at assessing the visually-grounded code generation capabilities of large multimodal models (LMMs). ChartMimic utilizes information-intensive visual charts and textual instructions as inputs, requiring LMMs to generate the corresponding code for chart rendering. ChartMimic includes 1,000 human-curated (figure, instruction, code) triplets, which represent the authentic chart use cases found in scientific papers across various domains(e.g., Physics, Computer Science, Economics, etc). These charts span 18 regular types and 4 advanced types, diversifying into 191 subcategories. Furthermore, we propose multi-level evaluation metrics to provide an automatic and thorough assessment of the output code and the rendered charts. Unlike existing code generation benchmarks, ChartMimic places emphasis on evaluating LMMs' capacity to harmonize a blend of cognitive capabilities, encompassing visual understanding, code generation, and cross-modal reasoning. The evaluation of 3 proprietary models and 11 open-weight models highlights the substantial challenges posed by ChartMimic. Even the advanced GPT-4V, Claude-3-opus only achieve an average score of 73.2 and 53.7, respectively, indicating significant room for improvement. We anticipate that ChartMimic will inspire the development of LMMs, advancing the pursuit of artificial general intelligence.

https://huggingface.co/discussions/paper/666fdf3ec16d62cbb045cb8f