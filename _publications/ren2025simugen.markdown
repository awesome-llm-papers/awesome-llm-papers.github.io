---
layout: publication
title: 'Simugen: Multi-modal Agentic Framework For Constructing Block Diagram-based
  Simulation Models'
authors: Ren Xinxing, Zang Qianbo, Guo Zekun
conference: Journal of Petroleum Technology
year: 2025
bibkey: ren2025simugen
citations: 148
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.15695'}]
tags: [RAG, Training Techniques, Agentic, Tools, Reinforcement Learning, Multimodal
    Models, LLM For Code]
---
Recent advances in large language models (LLMs) have shown impressive performance in mathematical reasoning and code generation. However, LLMs still struggle in the simulation domain, particularly in generating Simulink models, which are essential tools in engineering and scientific research. Our preliminary experiments indicate that LLM agents often fail to produce reliable and complete Simulink simulation code from text-only inputs, likely due to the lack of Simulink-specific data in their pretraining. To address this challenge, we propose SimuGen, a multimodal agent-based framework that automatically generates accurate Simulink simulation code by leveraging both the visual Simulink diagram and domain knowledge. SimuGen coordinates several specialized agents, including an investigator, unit test reviewer, code generator, executor, debug locator, and report writer, supported by a domain-specific knowledge base. This collaborative and modular design enables interpretable, robust, and reproducible Simulink simulation generation. Our source code is publicly available at https://github.com/renxinxing123/SimuGen_beta.