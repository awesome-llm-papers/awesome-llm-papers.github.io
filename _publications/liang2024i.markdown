---
layout: publication
title: 'I-SHEEP: Self-alignment Of LLM From Scratch Through An Iterative Self-enhancement
  Paradigm'
authors: Yiming Liang, Ge Zhang, Xingwei Qu, Tianyu Zheng, Jiawei Guo, Xinrun Du,
  Zhenzhu Yang, Jiaheng Liu, Chenghua Lin, Lei Ma, Wenhao Huang, Jiajun Zhang
conference: No Venue
year: 2024
bibkey: liang2024i
additional_links: [{name: Code, url: 'https://anonymous.4open.science/r/I-SHEEP'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/66bedfa4ac74db25de04bd70'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2408.08072'}]
tags: ["Datasets", "Evaluation", "Llm For Code"]
short_authors: Liang et al.
---
Large Language Models (LLMs) have achieved significant advancements, however, the common learning paradigm treats LLMs as passive information repositories, neglecting their potential for active learning and alignment. Some approaches train LLMs using their own generated synthetic data, exploring the possibility of active alignment. However, there is still a huge gap between these one-time alignment methods and the continuous automatic alignment of humans. In this paper, we introduce I-SHEEP, an Iterative Self-EnHancEmEnt Paradigm.This human-like paradigm enables LLMs to continuously self-align from scratch with nothing. Compared to the one-time alignment method Dromedary sun2023principledriven, which refers to the first iteration in this paper, I-SHEEP can significantly enhance capacities on both Qwen and Llama models. I-SHEEP achieves a maximum relative improvement of 78.2% in the Alpaca Eval, 24.0% in the MT Bench, and an absolute increase of 8.88% in the IFEval accuracy over subsequent iterations in Qwen-1.5 72B model. Additionally, I-SHEEP surpasses the base model in various standard benchmark generation tasks, achieving an average improvement of 24.77% in code generation tasks, 12.04% in TrivialQA, and 20.29% in SQuAD. We also provide new insights based on the experiment results. Our codes, datasets, and models are available at https://anonymous.4open.science/r/I-SHEEP.

https://huggingface.co/discussions/paper/66bedfa4ac74db25de04bd70