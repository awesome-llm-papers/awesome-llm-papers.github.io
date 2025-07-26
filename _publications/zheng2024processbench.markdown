---
layout: publication
title: 'Processbench: Identifying Process Errors In Mathematical Reasoning'
authors: Chujie Zheng, Zhenru Zhang, Beichen Zhang, Runji Lin, Keming Lu, Bowen Yu,
  Dayiheng Liu, Jingren Zhou, Junyang Lin
conference: No Venue
year: 2024
bibkey: zheng2024processbench
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.06559'}]
tags: ["Datasets", "Evaluation", "Model Architecture", "Prompting", "Reinforcement Learning"]
short_authors: Zheng et al.
---
As language models regularly make mistakes when solving math problems, automated identification of errors in the reasoning process becomes increasingly significant for their scalable oversight. In this paper, we introduce ProcessBench for measuring the ability to identify erroneous steps in mathematical reasoning. It consists of 3,400 test cases, primarily focused on competition- and Olympiad-level math problems. Each test case contains a step-by-step solution with error location annotated by human experts. Models are required to identify the earliest step that contains an error, or conclude that all steps are correct. We conduct extensive evaluation on ProcessBench, involving two types of models: process reward models (PRMs) and critic models, where for the latter we prompt general language models to critique each solution step by step. We draw two main observations: (1) Existing PRMs typically fail to generalize to more challenging math problems beyond GSM8K and MATH. They underperform both critic models (i.e., prompted general language models) and our own trained PRM that is straightforwardly fine-tuned on the PRM800K dataset. (2) The best open-source model, QwQ-32B-Preview, has demonstrated the critique capability competitive with the proprietary model GPT-4o, despite that it still lags behind the reasoning-specialized o1-mini. We hope ProcessBench can foster future research in reasoning process assessment, paving the way toward scalable oversight of language models.

https://huggingface.co/discussions/paper/6757e136887c48188a1f503f