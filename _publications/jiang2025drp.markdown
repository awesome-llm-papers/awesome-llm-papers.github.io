---
layout: publication
title: 'DRP: Distilled Reasoning Pruning With Skill-aware Step Decomposition For Efficient
  Large Reasoning Models'
authors: Jiang Yuxuan, Li Dawei, Ferraro Frank
conference: Journal of Experimental &amp; Theoretical Artificial Intelligence
year: 2025
bibkey: jiang2025drp
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.13975'}]
tags: [RAG, Training Techniques, Distillation, Tools, Efficiency And Optimization,
  Pruning, Datasets]
---
While Large Reasoning Models (LRMs) have demonstrated success in complex reasoning tasks through long chain-of-thought (CoT) reasoning, their inference often involves excessively verbose reasoning traces, resulting in substantial inefficiency. To address this, we propose Distilled Reasoning Pruning (DRP), a hybrid framework that combines inference-time pruning with tuning-based distillation, two widely used strategies for efficient reasoning. DRP uses a teacher model to perform skill-aware step decomposition and content pruning, and then distills the pruned reasoning paths into a student model, enabling it to reason both efficiently and accurately. Across several challenging mathematical reasoning datasets, we find that models trained with DRP achieve substantial improvements in token efficiency without sacrificing accuracy. Specifically, DRP reduces average token usage on GSM8K from 917 to 328 while improving accuracy from 91.7% to 94.1%, and achieves a 43% token reduction on AIME with no performance drop. Further analysis shows that aligning the reasoning structure of training CoTs with the student's reasoning capacity is critical for effective knowledge transfer and performance gains.