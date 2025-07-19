---
layout: publication
title: 'When Graph Meets Multimodal: Benchmarking And Meditating On Multimodal Attributed
  Graphs Learning'
authors: Yan et al.
conference: Nature Machine Intelligence
year: 2024
bibkey: yan2024when
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.09132'}]
tags: [Ethics And Bias, Tools, Training Techniques, Evaluation, Applications, LLM
    for Code, Multimodal Models, Datasets, Reinforcement Learning]
---
Multimodal Attributed Graphs (MAGs) are ubiquitous in real-world
applications, encompassing extensive knowledge through multimodal attributes
attached to nodes (e.g., texts and images) and topological structure
representing node interactions. Despite its potential to advance diverse
research fields like social networks and e-commerce, MAG representation
learning (MAGRL) remains underexplored due to the lack of standardized datasets
and evaluation frameworks. In this paper, we first propose MAGB, a
comprehensive MAG benchmark dataset, featuring curated graphs from various
domains with both textual and visual attributes. Based on MAGB dataset, we
further systematically evaluate two mainstream MAGRL paradigms:
\\(\textit\{GNN-as-Predictor\}\\), which integrates multimodal attributes via Graph
Neural Networks (GNNs), and \\(\textit\{VLM-as-Predictor\}\\), which harnesses Vision
Language Models (VLMs) for zero-shot reasoning. Extensive experiments on MAGB
reveal following critical insights: \\(\textit\{(i)\}\\) Modality significances
fluctuate drastically with specific domain characteristics. \\(\textit\{(ii)\}\\)
Multimodal embeddings can elevate the performance ceiling of GNNs. However,
intrinsic biases among modalities may impede effective training, particularly
in low-data scenarios. \\(\textit\{(iii)\}\\) VLMs are highly effective at generating
multimodal embeddings that alleviate the imbalance between textual and visual
attributes. These discoveries, which illuminate the synergy between multimodal
attributes and graph topologies, contribute to reliable benchmarks, paving the
way for future MAG research. The MAGB dataset and evaluation pipeline are
publicly available at https://github.com/sktsherlock/MAGB.