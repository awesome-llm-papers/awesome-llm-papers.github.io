---
layout: publication
title: 'Llms For Knowledge Graph Construction And Reasoning: Recent Capabilities And
  Future Opportunities'
authors: Yuqi Zhu, Xiaohan Wang, Jing Chen, Shuofei Qiao, Yixin Ou, Yunzhi Yao, Shumin
  Deng, Huajun Chen, Ningyu Zhang
conference: World Wide Web
year: 2024
bibkey: zhu2023llms
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.13168'}]
tags: ["Agentic", "Datasets", "Evaluation", "Few-Shot", "GPT", "Has Code", "Model Architecture", "Reinforcement Learning"]
short_authors: Zhu et al.
---
This paper presents an exhaustive quantitative and qualitative evaluation of
Large Language Models (LLMs) for Knowledge Graph (KG) construction and
reasoning. We engage in experiments across eight diverse datasets, focusing on
four representative tasks encompassing entity and relation extraction, event
extraction, link prediction, and question-answering, thereby thoroughly
exploring LLMs' performance in the domain of construction and inference.
Empirically, our findings suggest that LLMs, represented by GPT-4, are more
suited as inference assistants rather than few-shot information extractors.
Specifically, while GPT-4 exhibits good performance in tasks related to KG
construction, it excels further in reasoning tasks, surpassing fine-tuned
models in certain cases. Moreover, our investigation extends to the potential
generalization ability of LLMs for information extraction, leading to the
proposition of a Virtual Knowledge Extraction task and the development of the
corresponding VINE dataset. Based on these empirical findings, we further
propose AutoKG, a multi-agent-based approach employing LLMs and external
sources for KG construction and reasoning. We anticipate that this research can
provide invaluable insights for future undertakings in the field of knowledge
graphs. The code and datasets are in https://github.com/zjunlp/AutoKG.