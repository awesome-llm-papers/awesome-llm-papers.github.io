---
layout: publication
title: 'MME: A Comprehensive Evaluation Benchmark For Multimodal Large Language Models'
authors: [chaoyou Fu, peixian Chen, yunhang Shen, yulei Qin, mengdan Zhang, xu Lin,
  jinrui Yang, xiawu Zheng, ke Li, xing Sun, yunsheng Wu, rongrong Ji]
conference: Arxiv
year: 2023
bibkey: chaoyou2023mme
citations: 66
additional_links: [{name: Code, url: 'https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation'},
  {name: Paper, url: 'http://arxiv.org/abs/2306.13394v4'}]
tags: ["Evaluation"]
short_authors: Fu et al.
---
Multimodal Large Language Model (MLLM) relies on the powerful LLM to perform
multimodal tasks, showing amazing emergent abilities in recent studies, such as
writing poems based on an image. However, it is difficult for these case
studies to fully reflect the performance of MLLM, lacking a comprehensive
evaluation. In this paper, we fill in this blank, presenting the first
comprehensive MLLM Evaluation benchmark MME. It measures both perception and
cognition abilities on a total of 14 subtasks. In order to avoid data leakage
that may arise from direct use of public datasets for evaluation, the
annotations of instruction-answer pairs are all manually designed. The concise
instruction design allows us to fairly compare MLLMs, instead of struggling in
prompt engineering. Besides, with such an instruction, we can also easily carry
out quantitative statistics. A total of 30 advanced MLLMs are comprehensively
evaluated on our MME, which not only suggests that existing MLLMs still have a
large room for improvement, but also reveals the potential directions for the
subsequent model optimization. The data application manner and online
leaderboards are released at
https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation.