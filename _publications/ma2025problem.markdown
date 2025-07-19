---
layout: publication
title: Problem-solving Logic Guided Curriculum In-context Learning For Llms Complex
  Reasoning
authors: Ma Xuetao, Jiang Wenbin, Huang Hua
conference: Intelligence
year: 2025
bibkey: ma2025problem
citations: 167
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.15401'}]
tags: [Prompting, Evaluation, IJCAI, In Context Learning, Efficiency And Optimization,
  AISTATS, UAI, AAAI, Datasets, LLM For Code]
---
In-context learning (ICL) can significantly enhance the complex reasoning capabilities of large language models (LLMs), with the key lying in the selection and ordering of demonstration examples. Previous methods typically relied on simple features to measure the relevance between examples. We argue that these features are not sufficient to reflect the intrinsic connections between examples. In this study, we propose a curriculum ICL strategy guided by problem-solving logic. We select demonstration examples by analyzing the problem-solving logic and order them based on curriculum learning. Specifically, we constructed a problem-solving logic instruction set based on the BREAK dataset and fine-tuned a language model to analyze the problem-solving logic of examples. Subsequently, we selected appropriate demonstration examples based on problem-solving logic and assessed their difficulty according to the number of problem-solving steps. In accordance with the principles of curriculum learning, we ordered the examples from easy to hard to serve as contextual prompts. Experimental results on multiple benchmarks indicate that our method outperforms previous ICL approaches in terms of performance and efficiency, effectively enhancing the complex reasoning capabilities of LLMs. Our project will be released at https://github.com/maxuetao/CurriculumICL