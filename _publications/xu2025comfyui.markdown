---
layout: publication
title: 'Comfyui-r1: Exploring Reasoning Models For Workflow Generation'
authors: Zhenran Xu, Yiyu Wang, Xue Yang, Longyue Wang, Weihua Luo, Kaifu Zhang, Baotian
  Hu, Min Zhang
conference: No Venue
year: 2025
bibkey: xu2025comfyui
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/684a33989b38e1e5a33a680c'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.09790'}]
tags: ["Model Architecture", "Tools"]
short_authors: Xu et al.
---
AI-generated content has evolved from monolithic models to modular workflows, particularly on platforms like ComfyUI, enabling customization in creative pipelines. However, crafting effective workflows requires great expertise to orchestrate numerous specialized components, presenting a steep learning curve for users. To address this challenge, we introduce ComfyUI-R1, the first large reasoning model for automated workflow generation. Starting with our curated dataset of 4K workflows, we construct long chain-of-thought (CoT) reasoning data, including node selection, workflow planning, and code-level workflow representation. ComfyUI-R1 is trained through a two-stage framework: (1) CoT fine-tuning for cold start, adapting models to the ComfyUI domain; (2) reinforcement learning for incentivizing reasoning capability, guided by a fine-grained rule-metric hybrid reward, ensuring format validity, structural integrity, and node-level fidelity. Experiments show that our 7B-parameter model achieves a 97% format validity rate, along with high pass rate, node-level and graph-level F1 scores, significantly surpassing prior state-of-the-art methods that employ leading closed-source models such as GPT-4o and Claude series. Further analysis highlights the critical role of the reasoning process and the advantage of transforming workflows into code. Qualitative comparison reveals our strength in synthesizing intricate workflows with diverse nodes, underscoring the potential of long CoT reasoning in AI art creation.

https://huggingface.co/discussions/paper/684a33989b38e1e5a33a680c