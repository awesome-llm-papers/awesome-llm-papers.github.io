---
layout: publication
title: 'Webthinker: Empowering Large Reasoning Models With Deep Research Capability'
authors: Xiaoxi Li, Jiajie Jin, Guanting Dong, Hongjin Qian, Yutao Zhu, Yongkang Wu,
  Ji-rong Wen, Zhicheng Dou
conference: No Venue
year: 2025
bibkey: li2025webthinker
additional_links: [{name: Code, url: 'https://github.com/RUC-NLPIR/WebThinker'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/6812d594060494e99e48361c'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.21776'}]
tags: ["Agentic", "Efficiency", "Has Code", "Reinforcement Learning", "Training Techniques"]
short_authors: Li et al.
---
Large reasoning models (LRMs), such as OpenAI-o1 and DeepSeek-R1, demonstrate impressive long-horizon reasoning capabilities. However, their reliance on static internal knowledge limits their performance on complex, knowledge-intensive tasks and hinders their ability to produce comprehensive research reports requiring synthesis of diverse web information. To address this, we propose WebThinker, a deep research agent that empowers LRMs to autonomously search the web, navigate web pages, and draft research reports during the reasoning process. WebThinker integrates a Deep Web Explorer module, enabling LRMs to dynamically search, navigate, and extract information from the web when encountering knowledge gaps. It also employs an Autonomous Think-Search-and-Draft strategy, allowing the model to seamlessly interleave reasoning, information gathering, and report writing in real time. To further enhance research tool utilization, we introduce an RL-based training strategy via iterative online Direct Preference Optimization (DPO). Extensive experiments on complex reasoning benchmarks (GPQA, GAIA, WebWalkerQA, HLE) and scientific report generation tasks (Glaive) demonstrate that WebThinker significantly outperforms existing methods and strong proprietary systems. Our approach enhances LRM reliability and applicability in complex scenarios, paving the way for more capable and versatile deep research systems. The code is available at https://github.com/RUC-NLPIR/WebThinker.

https://huggingface.co/discussions/paper/6812d594060494e99e48361c