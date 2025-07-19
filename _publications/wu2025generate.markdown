---
layout: publication
title: 'Generate, But Verify: Reducing Hallucination In Vision-language Models With
  Retrospective Resampling'
authors: Wu et al.
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2025
bibkey: wu2025generate
citations: 136
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.13169'}]
tags: [Datasets, RAG, EMNLP, Training Techniques, Tools, Evaluation, Applications,
  Multimodal Models, Responsible AI]
---
Vision-Language Models (VLMs) excel at visual understanding but often suffer from visual hallucinations, where they generate descriptions of nonexistent objects, actions, or concepts, posing significant risks in safety-critical applications. Existing hallucination mitigation methods typically follow one of two paradigms: generation adjustment, which modifies decoding behavior to align text with visual inputs, and post-hoc verification, where external models assess and correct outputs. While effective, generation adjustment methods often rely on heuristics and lack correction mechanisms, while post-hoc verification is complicated, typically requiring multiple models and tending to reject outputs rather than refine them. In this work, we introduce REVERSE, a unified framework that integrates hallucination-aware training with on-the-fly self-verification. By leveraging a new hallucination-verification dataset containing over 1.3M semi-synthetic samples, along with a novel inference-time retrospective resampling technique, our approach enables VLMs to both detect hallucinations during generation and dynamically revise those hallucinations. Our evaluations show that REVERSE achieves state-of-the-art hallucination reduction, outperforming the best existing methods by up to 12% on CHAIR-MSCOCO and 34% on HaloQuest. Our dataset, model, and code are available at: https://reverse-vlm.github.io.