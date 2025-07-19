---
layout: publication
title: 'Gthinker: Towards General Multimodal Reasoning Via Cue-guided Rethinking'
authors: Zhan et al.
conference: Nature Communications
year: 2025
bibkey: zhan2025gthinker
citations: 164
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.01078'}]
tags: [RAG, Training Techniques, Agentic, Evaluation, Reinforcement Learning, Multimodal
    Models, Datasets]
---
Despite notable advancements in multimodal reasoning, leading Multimodal Large Language Models (MLLMs) still underperform on vision-centric multimodal reasoning tasks in general scenarios. This shortfall stems from their predominant reliance on logic- and knowledge-based slow thinking strategies, while effective for domains like math and science, fail to integrate visual information effectively during reasoning. Consequently, these models often fail to adequately ground visual cues, resulting in suboptimal performance in tasks that require multiple plausible visual interpretations and inferences. To address this, we present GThinker (General Thinker), a novel reasoning MLLM excelling in multimodal reasoning across general scenarios, mathematics, and science. GThinker introduces Cue-Rethinking, a flexible reasoning pattern that grounds inferences in visual cues and iteratively reinterprets these cues to resolve inconsistencies. Building on this pattern, we further propose a two-stage training pipeline, including pattern-guided cold start and incentive reinforcement learning, designed to enable multimodal reasoning capabilities across domains. Furthermore, to support the training, we construct GThinker-11K, comprising 7K high-quality, iteratively-annotated reasoning paths and 4K curated reinforcement learning samples, filling the data gap toward general multimodal reasoning. Extensive experiments demonstrate that GThinker achieves 81.5% on the challenging comprehensive multimodal reasoning benchmark M\\(^3\\)CoT, surpassing the latest O4-mini model. It also shows an average improvement of 2.1% on general scenario multimodal reasoning benchmarks, while maintaining on-par performance in mathematical reasoning compared to counterpart advanced reasoning models. The code, model, and data will be released soon at https://github.com/jefferyZhan/GThinker.