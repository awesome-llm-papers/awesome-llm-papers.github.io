---
layout: publication
title: 'VCA: Video Curious Agent For Long Video Understanding'
authors: Yang et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: yang2024vca
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.10471'}]
tags: [RAG, Agentic, Tools, Evaluation, CVPR, Efficiency And Optimization, Reinforcement
    Learning, Fine Tuning, Datasets]
---
Long video understanding poses unique challenges due to their temporal
complexity and low information density. Recent works address this task by
sampling numerous frames or incorporating auxiliary tools using LLMs, both of
which result in high computational costs. In this work, we introduce a
curiosity-driven video agent with self-exploration capability, dubbed as VCA.
Built upon VLMs, VCA autonomously navigates video segments and efficiently
builds a comprehensive understanding of complex video sequences. Instead of
directly sampling frames, VCA employs a tree-search structure to explore video
segments and collect frames. Rather than relying on external feedback or
reward, VCA leverages VLM's self-generated intrinsic reward to guide its
exploration, enabling it to capture the most crucial information for reasoning.
Experimental results on multiple long video benchmarks demonstrate our
approach's superior effectiveness and efficiency.