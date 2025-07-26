---
layout: publication
title: 'Anycap Project: A Unified Framework, Dataset, And Benchmark For Controllable
  Omni-modal Captioning'
authors: Yiming Ren, Zhiqiang Lin, Yu Li, Gao Meng, Weiyun Wang, Junjie Wang, Zicheng
  Lin, Jifeng Dai, Yujiu Yang, Wenhai Wang, Ruihang Chu
conference: No Venue
year: 2025
bibkey: ren2025anycap
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.12841'}]
tags: ["Datasets", "Evaluation", "Tools"]
short_authors: Ren et al.
---
Controllable captioning is essential for precise multimodal alignment and instruction following, yet existing models often lack fine-grained control and reliable evaluation protocols. To address this gap, we present the AnyCap Project, an integrated solution spanning model, dataset, and evaluation. We introduce AnyCapModel (ACM), a lightweight plug-and-play framework that enhances the controllability of existing foundation models for omni-modal captioning without retraining the base model. ACM reuses the original captions from base models while incorporating user instructions and modality features to generate improved captions. To remedy the data scarcity in controllable multimodal captioning, we build AnyCapDataset (ACD), covering three modalities, 28 user-instruction types, and 300\,k high-quality data entries. We further propose AnyCapEval, a new benchmark that provides more reliable evaluation metrics for controllable captioning by decoupling content accuracy and stylistic fidelity. ACM markedly improves caption quality across a diverse set of base models on AnyCapEval. Notably, ACM-8B raises GPT-4o\'s content scores by 45% and style scores by 12%, and it also achieves substantial gains on widely used benchmarks such as MIA-Bench and VidCapBench.

https://huggingface.co/discussions/paper/6879bba721b37e676c8e41a0