---
layout: publication
title: 'COOCO -- Common Objects Out-of-context -- Semantic Violation In Scenes: Investigating
  Multimodal Context In Referential Communication'
authors: Merlo et al.
conference: Pattern Recognition Letters
year: 2025
bibkey: merlo2025cooco
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.22274'}]
tags: [RAG, Attention Mechanism, Model Architecture, Multimodal Models, Datasets]
---
Natural scenes provide us with rich contexts for object recognition and reference. In particular, knowing what type of scene one is looking at generates expectations about which objects will occur, and what their spatial configuration should be. Do Vision-Language Models (VLMs) learn to rely on scene contexts in a similar way, when generating references to objects? To address this question, we introduce the \textit\{Common Objects Out-of-Context (COOCO)\} dataset and test to what extent VLMs rely on scene context to refer to objects under different degrees of scene-object congruency, and different perturbations. Our findings show that models leverage scene context adaptively, depending on both the semantic relatedness between object and scene and the level of noise. In particular, models rely more on context under high target-scene congruence or when objects are degraded. Attention analysis reveals that successful object categorisation involves increased focus on the target in mid-level layers, especially under moderate noise, suggesting that VLMs dynamically balance local and contextual information for reference generation. We make our dataset, code and models available at \href\{https://github.com/cs-nlp-uu/scenereg\}\{https://github.com/cs-nlp-uu/scenereg\}.