---
layout: publication
title: 'Lumos: Learning Agents With Unified Data, Modular Design, And Open-source
  Llms'
authors: da Yin, Faeze Brahman, Abhilasha Ravichander, Khyathi Chandu, Kai-wei Chang,
  Yejin Choi, Bill Yuchen Lin
conference: No Venue
year: 2023
bibkey: yin2023lumos
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2311.05657'}]
tags: ["Model Architecture", "Tools"]
short_authors: Yin et al.
---
We introduce Lumos, a novel framework for training language agents that employs a unified data format and a modular architecture based on open-source large language models (LLMs). Lumos consists of three distinct modules: planning, grounding, and execution. The planning module breaks down a task into a series of high-level, tool-agnostic subgoals, which are then made specific by the grounding module through a set of low-level actions. These actions are subsequently executed by the execution module, utilizing a range of off-the-shelf tools and APIs. In order to train these modules effectively, high-quality annotations of subgoals and actions were collected and are made available for fine-tuning open-source LLMs for various tasks such as complex question answering, web tasks, and math problems. Leveraging this unified data and modular design, Lumos not only achieves comparable or superior performance to current, state-of-the-art agents, but also exhibits several key advantages: (1) Lumos surpasses GPT-4/3.5-based agents in complex question answering and web tasks, while equalling the performance of significantly larger LLM agents on math tasks; (2) Lumos outperforms open-source agents created through conventional training methods and those using chain-of-thoughts training; and (3) Lumos is capable of effectively generalizing to unseen interactive tasks, outperforming larger LLM-based agents and even exceeding performance of specialized agents.

https://huggingface.co/discussions/paper/65518d2efd13d5b5ec9f121f