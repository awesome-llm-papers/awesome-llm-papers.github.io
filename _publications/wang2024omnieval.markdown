---
layout: publication
title: 'Omnieval: An Omnidirectional And Automatic RAG Evaluation Benchmark In Financial
  Domain'
authors: Shuting Wang, Jiejun Tan, Zhicheng Dou, Ji-rong Wen
conference: No Venue
year: 2024
bibkey: wang2024omnieval
additional_links: [{name: Code, url: 'https://github.com/RUC-NLPIR/OmniEval\{https://github.com/RUC-NLPIR/OmniEval\'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67625f6a7fa2dfcfa4a26eef'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2412.13018'}]
tags: ["Evaluation", "Has Code", "RAG", "Tools"]
short_authors: Wang et al.
---
As a typical and practical application of Large Language Models (LLMs), Retrieval-Augmented Generation (RAG) techniques have gained extensive attention, particularly in vertical domains where LLMs may lack domain-specific knowledge. In this paper, we introduce an omnidirectional and automatic RAG benchmark, OmniEval, in the financial domain. Our benchmark is characterized by its multi-dimensional evaluation framework, including (1) a matrix-based RAG scenario evaluation system that categorizes queries into five task classes and 16 financial topics, leading to a structured assessment of diverse query scenarios; (2) a multi-dimensional evaluation data generation approach, which combines GPT-4-based automatic generation and human annotation, achieving an 87.47% acceptance ratio in human evaluations on generated instances; (3) a multi-stage evaluation system that evaluates both retrieval and generation performance, result in a comprehensive evaluation on the RAG pipeline; and (4) robust evaluation metrics derived from rule-based and LLM-based ones, enhancing the reliability of assessments through manual annotations and supervised fine-tuning of an LLM evaluator. Our experiments demonstrate the comprehensiveness of OmniEval, which includes extensive test datasets and highlights the performance variations of RAG systems across diverse topics and tasks, revealing significant opportunities for RAG models to improve their capabilities in vertical domains. We open source the code of our benchmark in https://github.com/RUC-NLPIR/OmniEval\{https://github.com/RUC-NLPIR/OmniEval\}.

https://huggingface.co/discussions/paper/67625f6a7fa2dfcfa4a26eef