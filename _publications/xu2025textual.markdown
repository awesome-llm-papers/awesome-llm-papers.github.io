---
layout: publication
title: Textual-to-visual Iterative Self-verification For Slide Generation
authors: Xu et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: xu2025textual
citations: 87
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.15412'}]
tags: [RAG, Agentic, Reinforcement Learning, CVPR]
---
Generating presentation slides is a time-consuming task that urgently
requires automation. Due to their limited flexibility and lack of automated
refinement mechanisms, existing autonomous LLM-based agents face constraints in
real-world applicability. We decompose the task of generating missing
presentation slides into two key components: content generation and layout
generation, aligning with the typical process of creating academic slides.
First, we introduce a content generation approach that enhances coherence and
relevance by incorporating context from surrounding slides and leveraging
section retrieval strategies. For layout generation, we propose a
textual-to-visual self-verification process using a LLM-based Reviewer +
Refiner workflow, transforming complex textual layouts into intuitive visual
formats. This modality transformation simplifies the task, enabling accurate
and human-like review and refinement. Experiments show that our approach
significantly outperforms baseline methods in terms of alignment, logical flow,
visual appeal, and readability.