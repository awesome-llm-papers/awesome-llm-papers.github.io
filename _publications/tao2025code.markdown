---
layout: publication
title: 'Code Graph Model (CGM): A Graph-integrated Large Language Model For Repository-level
  Software Engineering Tasks'
authors: Hongyuan Tao, Ying Zhang, Zhenhao Tang, Hongen Peng, Xukun Zhu, Bingchang
  Liu, Yingguang Yang, Ziyin Zhang, Zhaogui Xu, Haipeng Zhang, Linchao Zhu, Rui Wang,
  Hang Yu, Jianguo Li, Peng di
conference: No Venue
year: 2025
bibkey: tao2025code
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/68369bacaffae1c74f432a82'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.16901'}]
tags: ["Has Code", "Llm For Code", "Model Architecture", "Tools"]
short_authors: Tao et al.
---
Recent advances in Large Language Models (LLMs) have shown promise in function-level code generation, yet repository-level software engineering tasks remain challenging. Current solutions predominantly rely on proprietary LLM agents, which introduce unpredictability and limit accessibility, raising concerns about data privacy and model customization. This paper investigates whether open-source LLMs can effectively address repository-level tasks without requiring agent-based approaches. We demonstrate this is possible by enabling LLMs to comprehend functions and files within codebases through their semantic information and structural dependencies. To this end, we introduce Code Graph Models (CGMs), which integrate repository code graph structures into the LLM's attention mechanism and map node attributes to the LLM's input space using a specialized adapter. When combined with an agentless graph RAG framework, our approach achieves a 43.00% resolution rate on the SWE-bench Lite benchmark using the open-source Qwen2.5-72B model. This performance ranks first among open weight models, second among methods with open-source systems, and eighth overall, surpassing the previous best open-source model-based method by 12.33%.

https://huggingface.co/discussions/paper/68369bacaffae1c74f432a82