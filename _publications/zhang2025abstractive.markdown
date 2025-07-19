---
layout: publication
title: 'Abstractive Visual Understanding Of Multi-modal Structured Knowledge: A New
  Perspective For MLLM Evaluation'
authors: Zhang et al.
conference: Proceedings of the 29th ACM International Conference on Multimedia
year: 2025
bibkey: zhang2025abstractive
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.01293'}]
tags: [RAG, Evaluation, Model Architecture, Reinforcement Learning, Datasets]
---
Multi-modal large language models (MLLMs) incorporate heterogeneous modalities into LLMs, enabling a comprehensive understanding of diverse scenarios and objects. Despite the proliferation of evaluation benchmarks and leaderboards for MLLMs, they predominantly overlook the critical capacity of MLLMs to comprehend world knowledge with structured abstractions that appear in visual form. To address this gap, we propose a novel evaluation paradigm and devise M3STR, an innovative benchmark grounded in the Multi-Modal Map for STRuctured understanding. This benchmark leverages multi-modal knowledge graphs to synthesize images encapsulating subgraph architectures enriched with multi-modal entities. M3STR necessitates that MLLMs not only recognize the multi-modal entities within the visual inputs but also decipher intricate relational topologies among them. We delineate the benchmark's statistical profiles and automated construction pipeline, accompanied by an extensive empirical analysis of 26 state-of-the-art MLLMs. Our findings reveal persistent deficiencies in processing abstractive visual information with structured knowledge, thereby charting a pivotal trajectory for advancing MLLMs' holistic reasoning capacities. Our code and data are released at https://github.com/zjukg/M3STR