---
layout: publication
title: 'Scenegenagent: Precise Industrial Scene Generation With Coding Agent'
authors: Xia et al.
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2024
bibkey: xia2024scenegenagent
citations: 105
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.21909'}]
tags: [ICCV, Training Techniques, GPT, Agentic, Model Architecture, Reinforcement
    Learning, Fine Tuning, Datasets]
---
The modeling of industrial scenes is essential for simulations in industrial manufacturing. While large language models (LLMs) have shown significant progress in generating general 3D scenes from textual descriptions, generating industrial scenes with LLMs poses a unique challenge due to their demand for precise measurements and positioning, requiring complex planning over spatial arrangement. To address this challenge, we introduce SceneGenAgent, an LLM-based agent for generating industrial scenes through C# code. SceneGenAgent ensures precise layout planning through a structured and calculable format, layout verification, and iterative refinement to meet the quantitative requirements of industrial scenarios. Experiment results demonstrate that LLMs powered by SceneGenAgent exceed their original performance, reaching up to 81.0% success rate in real-world industrial scene generation tasks and effectively meeting most scene generation requirements. To further enhance accessibility, we construct SceneInstruct, a dataset designed for fine-tuning open-source LLMs to integrate into SceneGenAgent. Experiments show that fine-tuning open-source LLMs on SceneInstruct yields significant performance improvements, with Llama3.1-70B approaching the capabilities of GPT-4o. Our code and data are available at https://github.com/THUDM/SceneGenAgent .