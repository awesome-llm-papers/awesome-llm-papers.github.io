---
layout: publication
title: Single-to-mix Modality Alignment With Multimodal Large Language Model For Document
  Image Machine Translation
authors: Liang et al.
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2025
bibkey: liang2025single
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2507.07572'}]
tags: [RAG, EMNLP, Training Techniques, Tools, Efficiency And Optimization, Multimodal
    Models, Datasets]
---
Document Image Machine Translation (DIMT) aims to translate text within document images, facing generalization challenges due to limited training data and the complex interplay between visual and textual information. To address these challenges, we introduce M4Doc, a novel single-to-mix modality alignment framework leveraging Multimodal Large Language Models (MLLMs). M4Doc aligns an image-only encoder with the multimodal representations of an MLLM, pre-trained on large-scale document image datasets. This alignment enables a lightweight DIMT model to learn crucial visual-textual correlations during training. During inference, M4Doc bypasses the MLLM, maintaining computational efficiency while benefiting from its multimodal knowledge. Comprehensive experiments demonstrate substantial improvements in translation quality, especially in cross-domain generalization and challenging document image scenarios.