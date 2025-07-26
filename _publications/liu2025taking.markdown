---
layout: publication
title: Taking Notes Brings Focus? Towards Multi-turn Multimodal Dialogue Learning
authors: "Jiazheng Liu, Sipeng Zheng, B\xF6rje F. Karlsson, Zongqing Lu"
conference: No Venue
year: 2025
bibkey: liu2025taking
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.07002'}]
tags: ["Dialogue & Multi Turn"]
short_authors: Liu et al.
---
Multimodal large language models (MLLMs), built on large-scale pre-trained vision towers and language models, have shown great capabilities in multimodal understanding. However, most existing MLLMs are trained on single-turn vision question-answering tasks, which do not accurately reflect real-world human conversations. In this paper, we introduce MMDiag, a multi-turn multimodal dialogue dataset. This dataset is collaboratively generated through deliberately designed rules and GPT assistance, featuring strong correlations between questions, between questions and images, and among different image regions; thus aligning more closely with real-world scenarios. MMDiag serves as a strong benchmark for multi-turn multimodal dialogue learning and brings more challenges to the grounding and reasoning capabilities of MLLMs. Further, inspired by human vision processing, we present DiagNote, an MLLM equipped with multimodal grounding and reasoning capabilities. DiagNote consists of two modules (Deliberate and Gaze) interacting with each other to perform Chain-of-Thought and annotations respectively, throughout multi-turn dialogues. We empirically demonstrate the advantages of DiagNote in both grounding and jointly processing and reasoning with vision and language information over existing MLLMs.

https://huggingface.co/discussions/paper/67cfa818d212c9c504884689