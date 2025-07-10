---
layout: publication
title: Prompting Large Language Models With Rationale Heuristics For Knowledge-based
  Visual Question Answering
authors: Zhongjian Hu, Peng Yang, Bing Li, Fengyuan Liu
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
citations: 111
bibkey: hu2024prompting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.16936'}]
tags: [Tools, RAG, Prompting]
---
Recently, Large Language Models (LLMs) have been used for knowledge-based
Visual Question Answering (VQA). Despite the encouraging results of previous
studies, prior methods prompt LLMs to predict answers directly, neglecting
intermediate thought processes. We argue that prior methods do not sufficiently
activate the capacities of LLMs. We propose a framework called PLRH that
Prompts LLMs with Rationale Heuristics for knowledge-based VQA. The PLRH
prompts LLMs with Chain of Thought (CoT) to generate rationale heuristics,
i.e., intermediate thought processes, and then leverages the rationale
heuristics to inspire LLMs to predict answers. Experiments show that our
approach outperforms the existing baselines by more than 2.2 and 2.1 on OK-VQA
and A-OKVQA, respectively.