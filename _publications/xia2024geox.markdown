---
layout: publication
title: 'Geox: Geometric Problem Solving Through Unified Formalized Vision-language
  Pre-training'
authors: Xia et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2024
bibkey: xia2024geox
citations: 472
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.11863'}]
tags: [Training Techniques, Evaluation, Transformer, Model Architecture, Multimodal
    Models, AAAI, Datasets]
---
Despite their proficiency in general tasks, Multi-modal Large Language Models
(MLLMs) struggle with automatic Geometry Problem Solving (GPS), which demands
understanding diagrams, interpreting symbols, and performing complex reasoning.
This limitation arises from their pre-training on natural images and texts,
along with the lack of automated verification in the problem-solving process.
Besides, current geometric specialists are limited by their task-specific
designs, making them less effective for broader geometric problems. To this
end, we present GeoX, a multi-modal large model focusing on geometric
understanding and reasoning tasks. Given the significant differences between
geometric diagram-symbol and natural image-text, we introduce unimodal
pre-training to develop a diagram encoder and symbol decoder, enhancing the
understanding of geometric images and corpora. Furthermore, we introduce
geometry-language alignment, an effective pre-training paradigm that bridges
the modality gap between unimodal geometric experts. We propose a
Generator-And-Sampler Transformer (GS-Former) to generate discriminative
queries and eliminate uninformative representations from unevenly distributed
geometric signals. Finally, GeoX benefits from visual instruction tuning,
empowering it to take geometric images and questions as input and generate
verifiable solutions. Experiments show that GeoX outperforms both generalists
and geometric specialists on publicly recognized benchmarks, such as GeoQA,
UniGeo, Geometry3K, and PGPS9k.