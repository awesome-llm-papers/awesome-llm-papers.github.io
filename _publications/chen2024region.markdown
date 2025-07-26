---
layout: publication
title: Region-aware Text-to-image Generation Via Hard Binding And Soft Refinement
authors: Zhennan Chen, Yajie Li, Haofan Wang, Zhibo Chen, Zhengkai Jiang, Jun Li,
  Qian Wang, Jian Yang, Ying Tai
conference: No Venue
year: 2024
bibkey: chen2024region
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2411.06558'}]
tags: ["Applications"]
short_authors: Chen et al.
---
In this paper, we present RAG, a Regional-Aware text-to-image Generation method conditioned on regional descriptions for precise layout composition. Regional prompting, or compositional generation, which enables fine-grained spatial control, has gained increasing attention for its practicality in real-world applications. However, previous methods either introduce additional trainable modules, thus only applicable to specific models, or manipulate on score maps within cross-attention layers using attention masks, resulting in limited control strength when the number of regions increases. To handle these limitations, we decouple the multi-region generation into two sub-tasks, the construction of individual region (Regional Hard Binding) that ensures the regional prompt is properly executed, and the overall detail refinement (Regional Soft Refinement) over regions that dismiss the visual boundaries and enhance adjacent interactions. Furthermore, RAG novelly makes repainting feasible, where users can modify specific unsatisfied regions in the last generation while keeping all other regions unchanged, without relying on additional inpainting models. Our approach is tuning-free and applicable to other frameworks as an enhancement to the prompt following property. Quantitative and qualitative experiments demonstrate that RAG achieves superior performance over attribute binding and object relationship than previous tuning-free methods.

https://huggingface.co/discussions/paper/6738f5e45604c3c00519465d