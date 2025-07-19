---
layout: publication
title: Language Modeling By Language Models
authors: Cheng Junyan, Clark Peter, Richardson Kyle
conference: Arxiv
year: 2025
bibkey: cheng2025language
citations: 13185
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.20249'}]
tags: [Scaling Laws, RAG, Training Techniques, GPT, Prompting, Agentic, Evaluation,
  Model Architecture, Efficiency And Optimization, Language Modeling, Security, Large
    Scale Training, Datasets, LLM For Code]
---
Can we leverage LLMs to model the process of discovering novel language model (LM) architectures? Inspired by real research, we propose a multi-agent LLM approach that simulates the conventional stages of research, from ideation and literature search (proposal stage) to design implementation (code generation), generative pre-training, and downstream evaluation (verification). Using ideas from scaling laws, our system, Genesys, employs a Ladder of Scales approach; new designs are proposed, adversarially reviewed, implemented, and selectively verified at increasingly larger model scales (14M\\(\sim\\)350M parameters) with a narrowing budget (the number of models we can train at each scale). To help make discovery efficient and factorizable, Genesys uses a novel genetic programming backbone, which we show has empirical advantages over commonly used direct prompt generation workflows (e.g., \\(\sim\\)86% percentage point improvement in successful design generation, a key bottleneck). We report experiments involving 1,162 newly discovered designs (1,062 fully verified through pre-training) and find the best designs to be highly competitive with known architectures (e.g., outperform GPT2, Mamba2, etc., on 6/9 common benchmarks). We couple these results with comprehensive system-level ablations and formal results, which give broader insights into the design of effective autonomous discovery systems.