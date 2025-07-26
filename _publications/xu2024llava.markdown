---
layout: publication
title: 'Llava-o1: Let Vision Language Models Reason Step-by-step'
authors: Guowei Xu, Peng Jin, Li Hao, Yibing Song, Lichao Sun, Li Yuan
conference: No Venue
year: 2024
bibkey: xu2024llava
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2411.10440'}]
tags: ["Model Architecture"]
short_authors: Xu et al.
---
Large language models have demonstrated substantial advancements in reasoning capabilities, particularly through inference-time scaling, as illustrated by models such as OpenAI's o1. However, current Vision-Language Models (VLMs) often struggle to perform systematic and structured reasoning, especially when handling complex visual question-answering tasks. In this work, we introduce LLaVA-o1, a novel VLM designed to conduct autonomous multistage reasoning. Unlike chain-of-thought prompting, LLaVA-o1 independently engages in sequential stages of summarization, visual interpretation, logical reasoning, and conclusion generation. This structured approach enables LLaVA-o1 to achieve marked improvements in precision on reasoning-intensive tasks. To accomplish this, we compile the LLaVA-o1-100k dataset, integrating samples from various visual question answering sources and providing structured reasoning annotations. Besides, we propose an inference-time stage-level beam search method, which enables effective inference-time scaling. Remarkably, with only 100k training samples and a simple yet effective inference time scaling method, LLaVA-o1 not only outperforms its base model by 8.9% on a wide range of multimodal reasoning benchmarks, but also surpasses the performance of larger and even closed-source models, such as Gemini-1.5-pro, GPT-4o-mini, and Llama-3.2-90B-Vision-Instruct.

https://huggingface.co/discussions/paper/673aa0826c12c4b98bda1a43