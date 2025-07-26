---
layout: publication
title: Progressive Multimodal Reasoning Via Active Retrieval
authors: Guanting Dong, Chenghao Zhang, Mengjie Deng, Yutao Zhu, Zhicheng Dou, Ji-rong
  Wen
conference: No Venue
year: 2024
bibkey: dong2024progressive
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.14835'}]
tags: ["Tools"]
short_authors: Dong et al.
---
Multi-step multimodal reasoning tasks pose significant challenges for multimodal large language models (MLLMs), and finding effective ways to enhance their performance in such scenarios remains an unresolved issue. In this paper, we propose AR-MCTS, a universal framework designed to progressively improve the reasoning capabilities of MLLMs through Active Retrieval (AR) and Monte Carlo Tree Search (MCTS). Our approach begins with the development of a unified retrieval module that retrieves key supporting insights for solving complex reasoning problems from a hybrid-modal retrieval corpus. To bridge the gap in automated multimodal reasoning verification, we employ the MCTS algorithm combined with an active retrieval mechanism, which enables the automatic generation of step-wise annotations. This strategy dynamically retrieves key insights for each reasoning step, moving beyond traditional beam search sampling to improve the diversity and reliability of the reasoning space. Additionally, we introduce a process reward model that aligns progressively to support the automatic verification of multimodal reasoning tasks. Experimental results across three complex multimodal reasoning benchmarks confirm the effectiveness of the AR-MCTS framework in enhancing the performance of various multimodal models. Further analysis demonstrates that AR-MCTS can optimize sampling diversity and accuracy, yielding reliable multimodal reasoning.

https://huggingface.co/discussions/paper/6764d822772d134796df3ff6