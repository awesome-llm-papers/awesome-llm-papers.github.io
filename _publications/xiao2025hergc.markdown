---
layout: publication
title: 'HERGC: Heterogeneous Experts Representation And Generative Completion For
  Multimodal Knowledge Graphs'
authors: Xiao Yongkang, Zhang Rui
conference: 2019 International Joint Conference on Neural Networks (IJCNN)
year: 2025
bibkey: xiao2025hergc
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.00826'}]
tags: [RAG, Training Techniques, Tools, Evaluation, Reinforcement Learning, Security,
  Multimodal Models, Datasets]
---
Multimodal knowledge graphs (MMKGs) enrich traditional knowledge graphs (KGs) by incorporating diverse modalities such as images and text. Multi-modal knowledge graph completion (MMKGC) seeks to exploit these heterogeneous signals to infer missing facts, thereby mitigating the intrinsic incompleteness of MMKGs. Existing MMKGC methods typically leverage only the information contained in the MMKGs under the closed-world assumption and adopt discriminative training objectives, which limits their reasoning capacity during completion. Recent generative completion approaches powered by advanced large language models (LLMs) have shown strong reasoning abilities in unimodal knowledge graph completion, but their potential in MMKGC remains largely unexplored. To bridge this gap, we propose HERGC, a Heterogeneous Experts Representation and Generative Completion framework for MMKGs. HERGC first deploys a Heterogeneous Experts Representation Retriever that enriches and fuses multimodal information and retrieves a compact candidate set for each incomplete triple. It then uses a Generative LLM Predictor fine-tuned on minimal instruction data to accurately identify the correct answer from these candidates. Extensive experiments on three standard MMKG benchmarks demonstrate HERGC's effectiveness and robustness, achieving state-of-the-art performance.